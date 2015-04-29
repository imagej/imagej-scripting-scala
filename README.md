[![](http://jenkins.imagej.net/job/scripting-Scala/lastBuild/badge/icon)](http://jenkins.imagej.net/job/scripting-Scala/)

# Scala Scripting

This library provides a
[JSR-223-compliant](https://en.wikipedia.org/wiki/Scripting_for_the_Java_Platform)
scripting plugin for the [Scala](http://scala-lang.org/) language.

It is implemented as a `ScriptLanguage` plugin for the [SciJava
Common](https://github.com/scijava/scijava-common) platform, which means that
in addition to being usable directly as a `javax.script.ScriptEngineFactory`,
it also provides some functionality on top, such as the ability to generate
lines of script code based on SciJava events.

For a complete list of scripting languages available as part of the SciJava
platform, see the
[Scripting](https://github.com/scijava/scijava-common/wiki/Scripting) page on
the SciJava Common wiki.
