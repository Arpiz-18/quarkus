# Picocli Example

Hello and goodbye are civilization fundamentals. Let's not forget it with this picocli application by changing the `command` and `parameters`.

Also for picocli applications the dev mode is supported. When running dev mode, the picocli application is executed and on press of the Enter key, is restarted.

As picocli applications will often require arguments to be passed on the commandline, this is also possible in dev mode via:
```shell script
{buildtool.cli} {buildtool.cmd.dev} {#if buildtool.cli == 'gradle'}--quarkus-args{#else}-Dquarkus.args={/if}='help'
```

Guide: https://quarkus.io/guides/picocli
