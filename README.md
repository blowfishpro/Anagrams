# Anagrams

Python script for generating a list of anagrams from a word list

Usage: python anagrams.py [-h] [-w WORDLIST] [-o OUTPUT] [-m MINLETTERS] [-c] [-x]
                   [-p] [-v]

Arguments:

*  -h, --help            show this help message and exit
*  -w WORDLIST, --wordlist WORDLIST
                        Text file containing word list to analyze. If not
                        specified, will search for system dictionaries in
                        common locations.
*  -o OUTPUT, --output OUTPUT
                        Text file to write output to.
*  -m MINLETTERS, --minletters MINLETTERS
                        Minimum number of letters in a word for it to be
                        considered for anagram search. Minimum is 2. Default
                        is 4.
*  -c, --ignore-captials
                        If set, ignore capitalization (words that differ by
                        capitalization will be considered anagrams. Has no
                        effect if -i, --exclude-capitals is set.
*  -x, --exclude-capitals
                        If set, discard any capitalized words (proper names).
*  -p, --print           If set, print output of anagrams to stdout. Set
                        regardless if no -o, --output specified.
*  -v, --verbose         If set, make output verbose output.