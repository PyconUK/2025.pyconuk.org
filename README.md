# 202x.pyconuk.org
PyCon UK 202x website

If you're starting with this base, you'll need to update the dates, etc in the `_config.yml` to reflect those for the current year.
You probably only need to care about the stuff that is called con_<something>.
You'll also need to put appropriate links everywhere you find "There will be a link".
Also, don't forget to update the 'Schedule' link in the header when the schedule is available.

## Building Locally
### Installing Jekyll

This site is made using [Jekyll](https://jekyllrb.com).
Jekyll is a static site generator written in ruby.
To build the project we first need to check that we have Jekyll's requirements installed.

These are:

* [Ruby](https://www.ruby-lang.org/en/downloads/) (tested with Ruby 3.0.2- you will also need the development headers)
* [RubyGems](https://rubygems.org/pages/download)
* [GCC](https://gcc.gnu.org/install/)
* [Make](https://www.gnu.org/software/make/)

On Ubuntu 22.04 this can be achieved by: sudo apt-get install -y ruby ruby-dev gcc make build-essential

You can check if you have these installed by typing `<command> -v` in your terminal.
If the program is available on your system then you should see the version of the program that is installed outputted in your terminal.

For example if Ruby in installed and you run `ruby -v`, you should get output like this `ruby 3.0.2p107 (2021-07-07 revision 0db68f0233) [x86_64-linux-gnu]`.
If RubyGems is not installed an you run `gem -v` you should get an error like this `bash: gem: command not found`

See the [Jekyll documentation](https://jekyllrb.com/docs/installation/) for more information on install Jekyll and its requirements.

Now that you have all of Jekyll's requirements installed you can install and run Jekyll:

```bash
./run
```

This will start a webserver on [http://127.0.0.1:4020/](http://127.0.0.1:4020/).
To view the website open [http://127.0.0.1:4020/](http://127.0.0.1:4020/) in your favorite web browser.
This will also automatically rebuild the project when a change to the source is detected.

If you change the `_config.yml`, you will need to restart.

If port 4020 is not available on your computer, you can run on another port with `--port <another port>`, e.g. `./run --port 4090`
You can disable livereload with `--nolivereload`, and not show future blog posts (the default after deployment, see below) with `--nofuture`.
If you need to check options, run `./run --help` to see available flags/etc which you can then pass directly to `./run`.

### Adding blog posts

Blog posts live in `src/_posts`. Each post is a file with a name of the form
`2025-01-30-<some-name>.md`; for example `2025-01-30-new-year-new-pycon.md`.

**Note a post with a date in the future will not automatically get deployed
when the main branch is updated. A manual deployment run will be required on or
after the post date.**
