.. git-review documentation master file, created by
   sphinx-quickstart on Sun Sep 25 09:00:23 2011.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

==========
git-review
==========

SYNOPSIS
--------

:program:`git-review` [:ref:`OPTIONS <git-review-options-label`] [*BRANCH*]

DESCRIPTION
-----------

:program:`git-review` automates and streamlines some of the tasks involve with
submitting local changes to a *Gerrit* server for review.

.. _git-review-options-label:

OPTIONS
-------

.. program:: git-review

.. option:: --topic, -t

  Sets the target topic for this change on the gerrit server.

.. option:: --dry-run, -n

  Don't actually perform any commands that have direct effects. Print them
  instead.

.. option:: --no-rebase, -R

  Do not automatically perform a rebase before submitting the change to
  gerrit.

.. option:: --update, -R

  Skip cached local copies and force updates from network resources.

.. option:: --verbose, -v

  Turns on more verbose output.

