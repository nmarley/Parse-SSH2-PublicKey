# Parse-SSH2-PublicKey

Version: 0.01

This module parses SSH2 public keys from text files. It can parse both
OpenSSH and SECSH key file formats and will parse multiple keys out of a
file/text block, even parsing mixed-format files (e.g. a file containing
both OpenSSH- and SECSH-format keys). This module was created to assist
sysadmins in converting from one SSH implementation to another.

## Installation

To install this module, run the following commands:

    perl Makefile.PL
    make
    make test
    make install

## Support and Documentation

After installing, you can find documentation for this module with the
perldoc command.

    perldoc Parse::SSH2::PublicKey

### You can also look for information at:

  https://github.com/nmarley/Parse-SSH2-PublicKey

## License

Released under the MIT License.  See the [LICENSE][] file for further details.

[license]: LICENSE
