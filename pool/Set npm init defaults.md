# Set Npm Init Defaults

Some defaults are just the NPM-provided conventions. They don’t know much more to provide.
But you can provide your own defaults for your system by editing ~/.npmrc. Or you can use
the cli to add to this file from the terminal. For instance, the two I like to change are
my author name and the license:

npm config set init-author-name "jaketrent" npm config set init-license "MIT"

Now, you can init and just take the defaults without pressing enter to answer the question
with:

npm -y

And what you get are the defaults you’ve already decided you like.

To know what other things you can change as defaults, use npm help 7 config and grep for
init--prefixed values. Happy npm’ing!
