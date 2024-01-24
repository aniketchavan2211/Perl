## Perl

### Introduction

**Perl** is a programming language developed by Larry Wall, especially designed for text processing. 
It stands for Practical Extraction and Report Language. It runs on a variety of platforms, such as Windows, Mac OS, and the various versions of UNIX. 
This tutorial provides a complete understanding on Perl.

#### Why to Learn Perl?

1. Perl is a stable, cross platform programming language.

2. Though Perl is not officially an acronym but few people used it as Practical Extraction and Report Language.

3. It is used for mission critical projects in the public and private sectors.

4. Perl is an Open Source software, licensed under its Artistic License, or the GNU General Public License (GPL).

5. Perl was created by Larry Wall.

6. Perl 1.0 was released to usenet's alt.comp.sources in 1987.

7. At the time of writing this tutorial, the latest version of perl was 5.16.2.

8. Perl is listed in the Oxford English Dictionary.

#### Perl Features

1. Perl takes the best features from other languages, such as C, awk, sed, sh, and BASIC, among others.

2. Perls database integration interface DBI supports third-party databases including Oracle, Sybase, Postgres, MySQL and others.

3. Perl works with HTML, XML, and other mark-up languages.

4. Perl supports Unicode.

5. Perl is Y2K compliant.

6. Perl supports both procedural and object-oriented programming.

7. Perl interfaces with external C/C++ libraries through XS or SWIG.

8. Perl is extensible. There are over 20,000 third party modules available from the Comprehensive Perl Archive Network (CPAN).

9. The Perl interpreter can be embedded into other systems.


#### Hello World !!!

Lets start with `Hello, World` programs with `PERL`. open any IDE or any Code Editors, start the PERL script with
`#!/usr/bin/perl` then write `print` built-in functions, write messages in double quotes `""` the end the statements with `;` semicolon. 

```perl
#!/usr/bin/perl

print "Hello, World !!!";

print("Hello, Perl !!!");
```

#### Applications of Perl

1. Perl used to be the most popular web programming language due to its text manipulation capabilities and rapid development cycle.

2. Perl is widely known as "the duct-tape of the Internet".

3. Perl can handle encrypted Web data, including e-commerce transactions.

4. Perl can be embedded into web servers to speed up processing by as much as 2000%.

5. Perl's mod_perl allows the Apache web server to embed a Perl interpreter.

6. Perl's DBI package makes web-database integration easy

**Perl** is an interpreted language, which means that your code can be run as is, without a compilation stage that creates a non portable executable program. Traditional compilers convert programs into machine language. When you run a Perl program, it's first compiled into a byte code, which is then converted ( as the program runs) into machine instructions. So it is not quite the same as shells, or Tcl, which are strictly interpreted without an intermediate representation. It is also not like most versions of C or C++, which are compiled directly into a machine dependent format. It is somewhere in between, along with Python and awk and Emacs .elc files.

#### Installations

Installing perl in linux:
```bash
sudo apt install perl -y
```

Check versions of `PERL Interpreter`.

```bash
perl -v 
# perl --version
```

One - Liner Commands

```bash
perl -e 'print "Hello, World"'
# Heloo, World
```

#### Comments

Comments are code that are ignored by Perl interpreter.

##### Single - Line 

```perl
# Single - Line Comments
```

##### Multi - Line 

Start with comment with `=begin` end with `=cut`

```perl
=begin 

Multi
Line
Comments

=cut
```

#### Whitespaces

Perl does't not care about whitespaces.

```perl
print     "Hello, World";
# Output: Hello, World
```

```perl
print "Hello
        , world";
# Hello
#   , world
```

#### Single and Double Quotes

**Snippets**:
```perl
#!/usr/bin/perl

print "Hello, world\n";
print 'Hello, world\n';
```

**Output**:
```
Hello, world
Hello, world\n$
```

Here `'` single line can't hide `\n` escape characters.
