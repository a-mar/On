# On
On the side escapades
and shenanigans.

I'm obviously new to this. :P

### Sample thesis documents
* [Lincoln (Sub/section numbers *WITHIN* margins)](http://j.mp/lincolnu1)
* [Lincoln (Sub/section numbers *OUTSIDE* margins)](http://j.mp/lincolnu2)
* [Melbourne (Minion Title Page)](http://bit.ly/1JEYk7C)
* [Melbourne (Fira Title Page)](http://bit.ly/1I1iliU)

### myapalike.bst 
This was an edit of the [apalike.bst](http://ftp.cs.stanford.edu/tex/bibtex/apalike.bst) file to look like [Plant Physiology](http://www.plantphysiol.org/) referencing ouput.
###### Some concerns:
* The `.bib` file accompanying this referencing style should have the `number = {}` entry empty for `@article` types.
* Names having `van de/der` should be written in the `.bib` file like `{van der Graaf}, Bjorn J` since there is a bug where the style file recognises the name `van Surname` and writes it as such but does not recognise the `van de/der` and writes it as `vande/der Surname` without any space between the `van` and `de/der`. So the fix is to write the surname in curly brackets as you want them to appear in the referencing, as shown above.
* [Abbreviated journal](http://images.webofknowledge.com/images/help/WOS/A_abrvjt.html) names should also be used in the `journal = {}` entry

The reference entry for journal articles comes out as:

**Surname FMI, Second FMI, Third, FM** (YYYY) The title of the journal article. Abbreviated Name of the Journal. **vol:** pp&ndash;pp

Example:

**Atmodjo MA, Hao Z, Mohnen D** (2013) Evolving views of pectin biosynthesis. Annu Rev Plant Biol. **64:** 747&ndash;779






### Licence or disclaimer

The whole bunch of codes is distributed under the [MIT Licence](https://opensource.org/licenses/MIT) which means, as far as my poor understanding allows it:

The codes here are provided free of charge with no strings attached whatsoever&mdash;one can tweak and revise and even pass it on as theirs to their heart's content&mdash;BUT I'm not liable for any error whatsoever, ergo, don't blame me if it does not work. As it stands, the whole thing is buggy, and one can clean it up if they wish to&mdash;that would be more awesome in fact.

Enjoy. &#9786;
