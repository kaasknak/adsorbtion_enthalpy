### Adsorption enthalpy.
This repo aims towards collecting as many adsorption enthalpies as can be found.
Every entry in this repo should contain the source to the literature where this value is found.
In some cases semi-empirical formulas are used. These will be included as well if found.

An alphabetical list of all the surfaces included in this repo can be found [here][list]

### Contributing
In order to add an enthalpy do the following:
 1. Create a file called `materials/<adsorbent>.md` (if this file already exists continue to step 3.
 2. Put this file in the folder `materials`
 3. Add a line to your newly created file at the proper alphabetical place for your adsorbate(s).
 4. `| Adsorbate_name | Enthalpy_value (in kJ/mol) | source |`
 5. If your source is a scientific paper please add the source using the following syntax `[DOI](http://doilink)` where `http://doilink` is the DOI-link of the article. If the link is a book or some other source please write it out clearly and consise so others can find it.
 6. If required add your adsorbent to the `materials/masterials.md` file.
 7. Send a pull request and I will merge it to the master branch.

If you have a formula / semi-empirical formula that does not lend itself to a single table value you might have to be a bit more creative.
In this case please commit the formula to a seperate file called `materials<adsorbent>formula.md`.
Due to the nature of these commits styling requirements will not be a stringent as in the table but try to keep it concise and keep the file easy for people to look through using CTRL+F. I might rewrite commits of this nature more to fit this style.

### Mistakes
All data found here should be checked with the given source. Don't copy data from here and expect it to be right!
If you do find a mistake please send a pull request and explain why it is wrong or open up an issue.

[list]: materials/materials.md
