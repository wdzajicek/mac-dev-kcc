# Install RVM

<https://rvm.io/>

To install RVM and Ruby
  -      // request RVM keys
        $ gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB

        // download and install RVM
        $ \curl -sSL <https://get.rvm.io> | bash -s stable

## Troubleshooting RVM Installation

  - If gpg command is unrecognized it is not installed (install with brew mentioned in Homebrew branch: <https://github.com/wdzajicek/mac-dev-kcc/tree/01-homebrew/#readme>)
  - The RVM KEYSERVER gave many issues.
  - hkp://keys.gnupg.net kept returning "no route to host"
  - To get key I had to run command via sudo, and change server to hkp://pgp.mit.edu
  -      $ sudo gpg --keyserver hkp://pgp.mit.edu --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB

          // Download and install RVM
          $ \curl -sSL https://get.rvm.io | bash

Next, Install Ruby via RVM: <https://github.com/wdzajicek/mac-dev-kcc/tree/03-ruby/#readme>
