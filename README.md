# vahub documentation

Reference docs for [vahub](https://github.com/LynnDelpy/vahub), a self-hosted
voice-assistant hub, and its [modules](https://github.com/LynnDelpy/vahub-modules).

Start with the vahub README for a five-minute overview. These pages go deeper.

## Pages

- [Architecture](architecture.md). The components, the one path every action
  takes, and why each piece is separate.
- [Configuration](configuration.md). Every `vahub.yaml` setting, secrets,
  environment overrides.
- [Security](security.md). The policy gate, the login, argument constraints, the
  confirmation flow, and what is not defended.
- [CLI](cli.md). Every `vahub` command.
- [Writing modules](writing-modules.md). The module contract, step by step.
- [Deployment](deployment.md). Docker, systemd, the reverse proxy, backups.
- [FAQ](faq.md). The questions people actually ask.

Docs track the code. If a page and the code disagree, the code wins; please open
an issue on the vahub repo.
