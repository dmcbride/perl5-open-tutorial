Plans for rewriting perlopentut
===============================

- Mention where the reference documentation is so readers know where to get a fuller picture of what open can do beyond what the tutorial presents.
- Consider discussing STDIN and family as special constants, rather than bringing in the concept of bareword filehandles.
- Add a mention of DATA, which is currently missing.
- Describe better when it is safe to use 2-arg open, but encourage the use of 3-arg open by default.
- Explain when explicit close and checking it's return value is important.
- Add a section on specifying encoding in a more prominent location, including use of :raw for binary files.
- Use Getopt::Long for short options as well as long.
- Mention writing to a string: open my $fh, '>', \$str.
- Remove opening sockets and named pipes, which are already covered in perlipc, and aren't suitable for a tutorial. Consider moving file locking elsewhere.
- ...?

