rsync-srpm
==========

Wrapper for SRPM building tools for rsync an updated rsync for CentOS 7 and 8, and Fedora 32.

Building awscli
===============

Ideally, install "mock" and use that to build for both CentOS 7, 8, and Fedora 32.

* make # Make all distinct versions using "mock"

Building a compoenent, without "mock" and in the local working system,
can also be done for testing.

* make build

Installing rsync
=================

The relevant yum repository is built locally in 'repo'.

Nico Kadel-Garcia <nkadel@gmail.com>
