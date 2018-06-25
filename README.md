# A simple Mediawiki bundle

This bundle deploys a Mediawiki with MySQL, for a total of two units.

# Usage

You can deploy the single bundle with:

    juju deploy wiki-simple

After deployment you need to expose the Mediawiki service, either via the GUI or the CLI:

    juju expose wiki

Then run a `juju status wiki` to get the public address. The browse to that address in your browser to configure and use the wiki.
# wiki-simple
