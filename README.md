sudoers-d - Handy sudo Configuration Tweaks
-------------------------------------------

The [`sudoers.d`] subdirectory contains [sudoers(5)] configuration
fragments in files that can be put into the `/etc/sudoers.d/` file
on most Linux and other Unix distributions to change the behaviour
of the [sudo(1)] command.

We also provide an [`install-sudoers`] command that makes it easy to
install these (or any other) `sudoers` files into `/etc/sudoers.d/`.
It uses `visudo` to do this so that the file syntax is checked and the
permissions are set correctly.

[sudo(1)]: https://www.sudo.ws/man/1.8.18/sudo.man.html
[sudoers(5)]: https://www.sudo.ws/man/1.8.18/sudoers.man.html
