# VVV Auto Bootstrap Demo 1

**This demo is currently inoperable, waiting on [WP-CLI #853](https://github.com/wp-cli/wp-cli/issues/853). Try [demo 2](https://github.com/simonwheatley/vvv-demo-2) and [demo 3](https://github.com/simonwheatley/vvv-demo-3) instead.**

This is one of a series of demonstrations of the auto-sitesetup designed to be used with [Varying Vagrants Vagrant](https://github.com/10up/varying-vagrant-vagrants/).

This demo shows a site setup using just WP CLI and MySQL commands.

To get started:

1. If you don't already have it, clone the [Vagrant repo](https://github.com/simonwheatley/varying-vagrant-vagrants/tree/feature/auto-site-setup-xteam) (Simon's fork, the X-Team auto site setup branch for now),perhaps into your `~/Vagrants/` directory (you may need to create it if it doesn't already exist)
2. Install the Vagrant hosts updater: `vagrant plugin install vagrant-hostsupdater`
3. Clone this branch of this repo into the `www` directory of your Vagrant as `www/vvv-demo-1`
4. If your Vagrant is running, from the Vagrant directory run `vagrant halt`
5. Followed by `vagrant up --provision`.  Perhaps a cup of tea now? The provisioning may take a while.

Then you can visit [http://vvv-demo-1.dev/](http://vvv-demo-1.dev/)

