```

     _/_/_/                                                      _/            _/
  _/          _/_/_/  _/_/_/  _/_/    _/    _/  _/_/_/      _/_/_/    _/_/_/  _/    _/_/_/
 _/        _/    _/  _/    _/    _/  _/    _/  _/    _/  _/    _/  _/    _/  _/  _/    _/
_/        _/    _/  _/    _/    _/  _/    _/  _/    _/  _/    _/  _/    _/  _/  _/    _/
 _/_/_/    _/_/_/  _/    _/    _/    _/_/_/  _/    _/    _/_/_/    _/_/_/  _/    _/_/_/

```

**Asko Soukka's cool Cockpit plugins bundled with a spring boot App.**

See for more infos on the plugins here: [camunda-cockpit-plugins](https://github.com/datakurre/camunda-cockpit-plugins/)

What gives you this project:
* ready to use Spring Boot App.
* Gradle Build file instead of Maven (sorry I don't like XML).
* A simple way to update the plugins into this project.
* The famous Camunda Twitter Example to have a start.

## Run the App
`gradle run`

Open http://localhost:8887

## Update the plugins
The project comes with the plugins already added.
`/src/main/resources/META-INF/resources/webjars/camunda/app/cockpit/scripts`
>Be aware that this folder is a requirement that it works!

To update the plugins, all you have to do, is to run the provided Ammonite Script.

`amm ./update-plugin.sc`

If you do not want to install [Ammonite](http://ammonite.io), I think you can easily make a bash file from it (no magic there;).