# JAMgwt

## What is the JAM

The Java Adventure Machine (JAM) is a java/javascript based game scripting engine for browsers and desktop and android. The main purpose of the JAM engine is to allow game-building for browsers easy and painless. Additionally, the JAM supports a simple semantics engine, allowing for flexible and intuitive gamedesign.

#### No recompiles necessary for game updates

The JAM engine allows updates to the game possible without recompiling the whole engine. The JAM reads simple text-based files into the game, written in our own custom scripting language.

#### Scripting requires no coding knowledge

The JAM uses its own scripting language that allows the creation of scenes, puzzles, objects or adjustments without needing to understand the engine code.

#### Multi-use

The JAM supports text-adventures, point-and-clicks, isometric games, visual novels.

#### Semantics engine

The JAM supports a semantics engine (Super Simple Semantics) that fasciliates interaction based on properties and inheritance.

#### Flexible

The scripting language has been designed to be intuitive and flexible. It allows complex operations such as selection by property, passive listeners, collision maps support, path finding and object cloning.

#### Multi-platform

As of now, the JAM has been primarily designed with browser use in mind. We are in the process of pulling apart the core engine from the browser specific code, allowing use for various Java graphics engines such as libGDX.

## What do I need to build this?

You will need the following:

* Java 7
* JAMCore 
* Spiffy Resources
* GWT 2.7+
* Guava 18+

And these smaller libraries
* Super Simple Semantics (https://bitbucket.org/lostagain/supersimplesemantics)
* GWT lzma (https://github.com/archiecobbs/gwt-lzma)
* gwt-dnd (https://github.com/fredsa/gwt-dnd)
* gwt-voices (https://github.com/fredsa/gwt-voices)
* sph-gwt-widget (https://download.osgeo.org/webdav/geotools/sph-gwt-widgets/sph-gwt-widgets/)
