# Cool stuff about the find command in bash
Everyone knows and loves the "find" command, which can help you find files. It is formatted as 
`$find [directory] [expression] [options]`
here are some cool techniques
## Name
using the -name option allows you to search the directory by file name
### Examples
#### Command:
`$ find ./technical -name *.*.txt`
#### Result:
`./technical/911report/chapter-13.1.txt
./technical/911report/chapter-13.2.txt
./technical/911report/chapter-13.3.txt
./technical/911report/chapter-13.4.txt
./technical/911report/chapter-13.5.txt
./technical/plos/journal.pbio.0020001.txt
./technical/plos/journal.pbio.0020010.txt
./technical/plos/journal.pbio.0020012.txt
./technical/plos/journal.pbio.0020013.txt
./technical/plos/journal.pbio.0020019.txt
./technical/plos/journal.pbio.0020028.txt
./technical/plos/journal.pbio.0020035.txt
./technical/plos/journal.pbio.0020040.txt
./technical/plos/journal.pbio.0020042.txt
./technical/plos/journal.pbio.0020043.txt
./technical/plos/journal.pbio.0020046.txt
./technical/plos/journal.pbio.0020047.txt
./technical/plos/journal.pbio.0020052.txt
./technical/plos/journal.pbio.0020053.txt
./technical/plos/journal.pbio.0020054.txt
./technical/plos/journal.pbio.0020063.txt
./technical/plos/journal.pbio.0020064.txt
./technical/plos/journal.pbio.0020067.txt
./technical/plos/journal.pbio.0020068.txt
./technical/plos/journal.pbio.0020071.txt
./technical/plos/journal.pbio.0020073.txt
./technical/plos/journal.pbio.0020100.txt
./technical/plos/journal.pbio.0020101.txt
./technical/plos/journal.pbio.0020105.txt
./technical/plos/journal.pbio.0020112.txt
./technical/plos/journal.pbio.0020113.txt
./technical/plos/journal.pbio.0020116.txt
./technical/plos/journal.pbio.0020121.txt
./technical/plos/journal.pbio.0020125.txt
./technical/plos/journal.pbio.0020127.txt
./technical/plos/journal.pbio.0020133.txt
./technical/plos/journal.pbio.0020140.txt
./technical/plos/journal.pbio.0020145.txt
./technical/plos/journal.pbio.0020146.txt
./technical/plos/journal.pbio.0020147.txt
./technical/plos/journal.pbio.0020148.txt
./technical/plos/journal.pbio.0020150.txt
./technical/plos/journal.pbio.0020156.txt
./technical/plos/journal.pbio.0020161.txt
./technical/plos/journal.pbio.0020164.txt
./technical/plos/journal.pbio.0020169.txt
./technical/plos/journal.pbio.0020172.txt
./technical/plos/journal.pbio.0020183.txt
./technical/plos/journal.pbio.0020187.txt
./technical/plos/journal.pbio.0020190.txt
./technical/plos/journal.pbio.0020206.txt
./technical/plos/journal.pbio.0020213.txt
./technical/plos/journal.pbio.0020214.txt
./technical/plos/journal.pbio.0020215.txt
./technical/plos/journal.pbio.0020216.txt
./technical/plos/journal.pbio.0020223.txt
./technical/plos/journal.pbio.0020224.txt
./technical/plos/journal.pbio.0020228.txt
./technical/plos/journal.pbio.0020232.txt
./technical/plos/journal.pbio.0020241.txt
./technical/plos/journal.pbio.0020262.txt
./technical/plos/journal.pbio.0020263.txt
./technical/plos/journal.pbio.0020267.txt
./technical/plos/journal.pbio.0020272.txt
./technical/plos/journal.pbio.0020276.txt
./technical/plos/journal.pbio.0020297.txt
./technical/plos/journal.pbio.0020302.txt
./technical/plos/journal.pbio.0020306.txt
./technical/plos/journal.pbio.0020307.txt
./technical/plos/journal.pbio.0020310.txt
./technical/plos/journal.pbio.0020311.txt
./technical/plos/journal.pbio.0020337.txt
./technical/plos/journal.pbio.0020346.txt
./technical/plos/journal.pbio.0020347.txt
./technical/plos/journal.pbio.0020348.txt
./technical/plos/journal.pbio.0020350.txt
./technical/plos/journal.pbio.0020353.txt
./technical/plos/journal.pbio.0020354.txt
./technical/plos/journal.pbio.0020394.txt
./technical/plos/journal.pbio.0020400.txt
./technical/plos/journal.pbio.0020401.txt
./technical/plos/journal.pbio.0020404.txt
./technical/plos/journal.pbio.0020406.txt
./technical/plos/journal.pbio.0020419.txt
./technical/plos/journal.pbio.0020420.txt
./technical/plos/journal.pbio.0020430.txt
./technical/plos/journal.pbio.0020431.txt
./technical/plos/journal.pbio.0020439.txt
./technical/plos/journal.pbio.0020440.txt
./technical/plos/journal.pbio.0030021.txt
./technical/plos/journal.pbio.0030024.txt
./technical/plos/journal.pbio.0030032.txt
./technical/plos/journal.pbio.0030050.txt
./technical/plos/journal.pbio.0030051.txt
./technical/plos/journal.pbio.0030056.txt
./technical/plos/journal.pbio.0030062.txt
./technical/plos/journal.pbio.0030065.txt
./technical/plos/journal.pbio.0030076.txt
./technical/plos/journal.pbio.0030094.txt
./technical/plos/journal.pbio.0030097.txt
./technical/plos/journal.pbio.0030102.txt
./technical/plos/journal.pbio.0030105.txt
./technical/plos/journal.pbio.0030127.txt
./technical/plos/journal.pbio.0030129.txt
./technical/plos/journal.pbio.0030131.txt
./technical/plos/journal.pbio.0030136.txt
./technical/plos/journal.pbio.0030137.txt
./technical/plos/pmed.0010008.txt
./technical/plos/pmed.0010010.txt
./technical/plos/pmed.0010013.txt
./technical/plos/pmed.0010021.txt
./technical/plos/pmed.0010022.txt
./technical/plos/pmed.0010023.txt
./technical/plos/pmed.0010024.txt
./technical/plos/pmed.0010025.txt
./technical/plos/pmed.0010026.txt
./technical/plos/pmed.0010028.txt
./technical/plos/pmed.0010029.txt
./technical/plos/pmed.0010030.txt
./technical/plos/pmed.0010034.txt
./technical/plos/pmed.0010036.txt
./technical/plos/pmed.0010039.txt
./technical/plos/pmed.0010041.txt
./technical/plos/pmed.0010042.txt
./technical/plos/pmed.0010045.txt
./technical/plos/pmed.0010046.txt
./technical/plos/pmed.0010047.txt
./technical/plos/pmed.0010048.txt
./technical/plos/pmed.0010049.txt
./technical/plos/pmed.0010050.txt
./technical/plos/pmed.0010051.txt
./technical/plos/pmed.0010052.txt
./technical/plos/pmed.0010056.txt
./technical/plos/pmed.0010058.txt
./technical/plos/pmed.0010060.txt
./technical/plos/pmed.0010061.txt
./technical/plos/pmed.0010062.txt
./technical/plos/pmed.0010064.txt
./technical/plos/pmed.0010066.txt
./technical/plos/pmed.0010067.txt
./technical/plos/pmed.0010068.txt
./technical/plos/pmed.0010069.txt
./technical/plos/pmed.0010070.txt
./technical/plos/pmed.0010071.txt
./technical/plos/pmed.0020002.txt
./technical/plos/pmed.0020005.txt
./technical/plos/pmed.0020007.txt
./technical/plos/pmed.0020009.txt
./technical/plos/pmed.0020015.txt
./technical/plos/pmed.0020016.txt
./technical/plos/pmed.0020017.txt
./technical/plos/pmed.0020018.txt
./technical/plos/pmed.0020019.txt
./technical/plos/pmed.0020020.txt
./technical/plos/pmed.0020021.txt
./technical/plos/pmed.0020022.txt
./technical/plos/pmed.0020023.txt
./technical/plos/pmed.0020024.txt
./technical/plos/pmed.0020027.txt
./technical/plos/pmed.0020028.txt
./technical/plos/pmed.0020033.txt
./technical/plos/pmed.0020034.txt
./technical/plos/pmed.0020035.txt
./technical/plos/pmed.0020036.txt
./technical/plos/pmed.0020039.txt
./technical/plos/pmed.0020040.txt
./technical/plos/pmed.0020045.txt
./technical/plos/pmed.0020047.txt
./technical/plos/pmed.0020048.txt
./technical/plos/pmed.0020050.txt
./technical/plos/pmed.0020055.txt
./technical/plos/pmed.0020059.txt
./technical/plos/pmed.0020060.txt
./technical/plos/pmed.0020061.txt
./technical/plos/pmed.0020062.txt
./technical/plos/pmed.0020065.txt
./technical/plos/pmed.0020067.txt
./technical/plos/pmed.0020068.txt
./technical/plos/pmed.0020071.txt
./technical/plos/pmed.0020073.txt
./technical/plos/pmed.0020074.txt
./technical/plos/pmed.0020075.txt
./technical/plos/pmed.0020082.txt
./technical/plos/pmed.0020085.txt
./technical/plos/pmed.0020086.txt
./technical/plos/pmed.0020088.txt
./technical/plos/pmed.0020090.txt
./technical/plos/pmed.0020091.txt
./technical/plos/pmed.0020094.txt
./technical/plos/pmed.0020098.txt
./technical/plos/pmed.0020099.txt
./technical/plos/pmed.0020102.txt
./technical/plos/pmed.0020103.txt
./technical/plos/pmed.0020104.txt
./technical/plos/pmed.0020113.txt
./technical/plos/pmed.0020114.txt
./technical/plos/pmed.0020115.txt
./technical/plos/pmed.0020116.txt
./technical/plos/pmed.0020117.txt
./technical/plos/pmed.0020118.txt
./technical/plos/pmed.0020120.txt
./technical/plos/pmed.0020123.txt
./technical/plos/pmed.0020140.txt
./technical/plos/pmed.0020144.txt
./technical/plos/pmed.0020145.txt
./technical/plos/pmed.0020146.txt
./technical/plos/pmed.0020148.txt
./technical/plos/pmed.0020149.txt
./technical/plos/pmed.0020150.txt
./technical/plos/pmed.0020155.txt
./technical/plos/pmed.0020157.txt
./technical/plos/pmed.0020158.txt
./technical/plos/pmed.0020160.txt
./technical/plos/pmed.0020161.txt
./technical/plos/pmed.0020162.txt
./technical/plos/pmed.0020180.txt
./technical/plos/pmed.0020181.txt
./technical/plos/pmed.0020182.txt
./technical/plos/pmed.0020187.txt
./technical/plos/pmed.0020189.txt
./technical/plos/pmed.0020191.txt
./technical/plos/pmed.0020192.txt
./technical/plos/pmed.0020194.txt
./technical/plos/pmed.0020195.txt
./technical/plos/pmed.0020196.txt
./technical/plos/pmed.0020197.txt
./technical/plos/pmed.0020198.txt
./technical/plos/pmed.0020200.txt
./technical/plos/pmed.0020201.txt
./technical/plos/pmed.0020203.txt
./technical/plos/pmed.0020206.txt
./technical/plos/pmed.0020208.txt
./technical/plos/pmed.0020209.txt
./technical/plos/pmed.0020210.txt
./technical/plos/pmed.0020212.txt
./technical/plos/pmed.0020216.txt
./technical/plos/pmed.0020226.txt
./technical/plos/pmed.0020231.txt
./technical/plos/pmed.0020232.txt
./technical/plos/pmed.0020235.txt
./technical/plos/pmed.0020236.txt
./technical/plos/pmed.0020237.txt
./technical/plos/pmed.0020238.txt
./technical/plos/pmed.0020239.txt
./technical/plos/pmed.0020242.txt
./technical/plos/pmed.0020246.txt
./technical/plos/pmed.0020247.txt
./technical/plos/pmed.0020249.txt
./technical/plos/pmed.0020257.txt
./technical/plos/pmed.0020258.txt
./technical/plos/pmed.0020268.txt
./technical/plos/pmed.0020272.txt
./technical/plos/pmed.0020273.txt
./technical/plos/pmed.0020274.txt
./technical/plos/pmed.0020275.txt
./technical/plos/pmed.0020278.txt
./technical/plos/pmed.0020281.txt`

#### Command
`$ find ./technical -name 911*`
#### Result
`./technical/911report`

## Size
the -size tag allows you to search for files by size. Using -size +N searches for files with at least N blocks, and -N does at most. Adding a 'c' at the end allows to use character count.

### Examples

#### Command
`$ find ./technical -size +500`
#### Result
`./technical/911report/chapter-13.4.txt
./technical/911report/chapter-13.5.txt
./technical/911report/chapter-3.txt
./technical/government/Gen_Account_Office/d01591sp.txt
./technical/government/Gen_Account_Office/Statements_Feb28-1997_volume.txt`

#### Command
`$ find ./technical -name *.txt -size -1000c`
#### Result
`./technical/plos/pmed.0020191.txt
./technical/plos/pmed.0020226.txt`

## User
The -user tag allows you to specify the username of the file's owner
### Examples
#### Command
`$ find ./technical -name 911* -user aryad`
#### Result
`./technical/911report`
#### Command
`$ find ./technical -name 911* ! -user aryad`
#### Result
` `

## Exec
Using the -exec tag (or the -ok tag) allows you to execute a command on each of the files found

### Examples
#### Command
`$ find ./technical -type f -name "chapter-*.txt" -exec grep 'Bin Laden'  {} \;`

this command is searching through every text file matching chapter-\*.txt for lines containing "Bin Laden"

#### Result
`                terrorist leader, with the headline "U.S. Hard Put to Find Proof Bin Laden Directed
                www.npr.org/display_pages/features/feature_1253796.html). 14. "Bin Laden's 'Letter
                Fleecing Bin Laden," Wall Street Journal, Dec. 3, 2001, p. A1.
            87. For general information on Hage, see Oriana Gill, "Hunting Bin Laden: A Portrait
            93. ABC News interview, "Terror Suspect: An Interview with Osama Bin Laden," Dec. 22,
                Statements of Prosecutor and Judge, United States v. Bin Laden, No. S(7) 98 Cr. 1023
                FBI Special Agent Daniel Coleman, United States v. Usama Bin Laden, No. S(7) 98 Cr.
            109. Indictment, United States v. Usama Bin Laden, No. 98 Cr. (S.D. N.Y. unsealed
                Terrorism, Sudan Struck a Blow by Fleecing Bin Laden," Wall Street Journal, Dec. 3,
                Bin Laden: How Bill Clinton's Failures Unleashed Global Terror (Regnery, 2003),
                memo,"U.S. Engagement with the Taliban on Usama Bin Laden," undated (attached to NSC
            8. Tim Weiner, "U.S. Hard Put to Find Proof Bin Laden Directed Attacks," New York
                final aim is the restoration of the caliphate.'"Mehdi Mozaffari,"Bin Laden and
                to resolve the Bin Laden problem at the earliest possible time." But Zinni came back`
#### Command
`find ./technical -type f -name "chapter-*.txt" -exec rm {} \;`
 This command deletes all such files
 
#### Result
`$  find -name chapter-*.txt` yeidls no files, and the 911reports file is only left with the preface.txt file

# Source:
All commands were found on [GeeksForGeeks](https://www.geeksforgeeks.org/find-command-in-linux-with-examples/)
