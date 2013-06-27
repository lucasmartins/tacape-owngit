Tacape Owngit
=============

This is a tool to help you manage remote Bare Git repositories through SSH, assuming you have ssh_keys setup for authentication.

A lot of projects I want to keep safe+versioned don't deserve 'yet' to be created on GitHub/Bitbucket, maybe you're doodling some code and fear tomorrow your HD may not wake up.

So if you have a server with SSH service access, you can use it as your personal git repository.

## Install
```bash
 $ tacape install owngit
```

## Usage
### '"Blessing" a folder'
```bash
 $ mkdir new_doodle
 $ cd new_doodle
 $ tacape owngit add
```

### Listing remote repos
```bash
 $ tacape owngit list
 02#05-meuapp-arte-final.git
 03#05-elaborando-2.git
 03#06-user-profile.git
 coletor-de-precos.git
 dropbox-test.git
 estoque-hackerspace.git
 gm.git
 highrise-mapper-example.git
 highrise-mapper.git
 ...
```

### Cloning remote repos
```bash
 $ tacape owngit get highrise-mapper.git
```

Tacape tools
============

This is a work in progrees, I would wait until I have the testing suite implemented to publish this but time is slipping away from me, maybe you can help!

Just fork, add your tool, and make a pull request.

You can test your tools locally just throwing them at the `~/.tacape/tools` folder.

Take a look at the code of the tools already implemented.

All I did was to get the code of scripts I made for myself and put them togheter in a better organized way, this is not the kind of code you should publish, but I believe this is gonna force me to make it better.

Have fun!

This repo is used by [Tacape](https://github.com/lucasmartins/tacape)

Contribute
==========

Have any scripts laying around that you could be sharing? 

Just fork [Tacape Tools](https://github.com/lucasmartins/tacape-tools), add your tool, and make a pull request.

Support
=======

This is an opensource project so don't expect premium support, but don't be shy, post any troubles you're having in the [Issues](https://github.com/lucasmartins/tacape/issues) page and we'll do what we can to help.

License
=======

Tacape Tools is free software under the [MIT license](http://lucasmartins.mit-license.org).