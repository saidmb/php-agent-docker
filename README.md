# php-agent-docker

Sample app showing how to run the New Relic PHP Agent and Daemon in seperate containers.

With version [9.2.0.247](https://docs.newrelic.com/docs/release-notes/agent-release-notes/php-release-notes/php-agent-920247) of the New Relic PHP Agent, the PHP daemon and agent no longer have to reside on the same host and can now communicate over a IPv4 or IPv6 TCP socket. This can be configured via the `newrelic.daemon.address` setting in the agent and the `--address` command line option for the daemon.

For more information on this configuration, please refer to this forum post:

https://discuss.newrelic.com/t/relic-solution-php-agent-and-daemon-containers/84841
