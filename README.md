# dsh
A simple docker shell to avoid typing 'docker' each time and adding some aliases.

Equivalent of:
$ docker ps -a

Start the docker shell and type a short cut alias:
$ dsh
:dsh> psa

This written as a Perl read-execute-print-loop. You can edit the Perl script to
create your own docker short cuts.

