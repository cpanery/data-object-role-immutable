# NAME

Data::Object::Role::Immutable

# ABSTRACT

Immutable Role for Perl 5

# SYNOPSIS

    package Example;

    use Moo;

    with 'Data::Object::Role::Immutable';

    package main;

    my $example = Example->new;

# DESCRIPTION

This package provides a mechanism for making any derived object immutable.

# METHODS

This package implements the following methods:

## immutable

    immutable() : Object

The immutable method returns the invocant as an immutable object, and will
throw an error if an attempt is made to modify the underlying value.

- immutable example #1

        # given: synopsis

        $example->immutable;

# AUTHOR

Al Newkirk, `awncorp@cpan.org`

# LICENSE

Copyright (C) 2011-2019, Al Newkirk, et al.

This is free software; you can redistribute it and/or modify it under the terms
of the The Apache License, Version 2.0, as elucidated in the ["license
file"](https://github.com/iamalnewkirk/data-object-role-immutable/blob/master/LICENSE).

# PROJECT

[Wiki](https://github.com/iamalnewkirk/data-object-role-immutable/wiki)

[Project](https://github.com/iamalnewkirk/data-object-role-immutable)

[Initiatives](https://github.com/iamalnewkirk/data-object-role-immutable/projects)

[Milestones](https://github.com/iamalnewkirk/data-object-role-immutable/milestones)

[Contributing](https://github.com/iamalnewkirk/data-object-role-immutable/blob/master/CONTRIBUTE.md)

[Issues](https://github.com/iamalnewkirk/data-object-role-immutable/issues)
