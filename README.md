# Sample SFM to FLEx project
This repository contains files for illustrating how to use git as version control for tracking an SFM to FLEx project


It illustrates homographs, senses, lexical relations.

It has sub-entries and sub-sub-entries. They are implemented as SFM fields within the main SFM record, rather than as separate records with markers indicating the main entries. Subentries that occur under senses are not differentiated from ones that occur under the main entry.

### Useful Tools
Install Lingua::PigLatin if necessary (first line)
````bash
sudo cpan install Lingua::PigLatin
# to PigLatin
perl -pE 'use Lingua::PigLatin q[piglatin]; print piglatin($_);'
# to English (not quite right but almost)
perl -nE 'my @x = split ; foreach $x (@x) {$x =~ s/(.*?)(.)(w)*ay$/$2$1/; say $x}'
````


 ### Attribution
 Portions of this database were derived from en.wiktionary.org
