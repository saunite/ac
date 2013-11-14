#/* ac: Autoconnector
# *
# * ----------------------------------------------------------------------------
# * "THE BEER-WARE LICENSE" (Revision 42):
# * <saunite@gmail.com> wrote this file. As long as you retain this notice you
# * can do whatever you want with this stuff. If we meet some day, and you think
# * this stuff is worth it, you can buy a beer in return to André Saunite
# * (Thanks to Poul-Henning Kamp <phk@FreeBSD.ORG> for this amazing license)
# * ----------------------------------------------------------------------------
# *
# * ac -> Auto Connector (or André's Connector) :P
# *
# * This is a Terminal connection manager (no GUI), intended to be used with 
# * your favorite Terminal application (Konsole, Gnome-Terminal, yakuake, and 
# * so on) or to be used in machines with no GUI available.
# *
# * Creation date: 2012/09/06
# * Last change: 2013/11/14
# *
# * ----------------------------------------------------------------------------
# *
# * Installation Instruction
# * 
# * For ac to run correctly, some perl modules need to be installed, in Debian
# * you can just install those packages:
# * 
# * perl-modules
# * libcrypt-ecb-perl
# * libexpect-perl
# * libterm-readkey-perl
# * libcrypt-blowfish-perl
# * libio-stty-perl
# * 
# * In case you are using another system or prefere to install all via CPAN, 
# * do the following:
# * 
# * Enter cpan:
# * 
# * $ sudo cpan
# * 
# * Run the installation of the needed modules:
# * 
# * install Expect
# * install Term::ReadKey
# * install Getopt::Std
# * install Crypt::EBC
# * install Crypt::Blowfish
# * install IO::Stty
# * 
# * ----------------------------------------------------------------------------
