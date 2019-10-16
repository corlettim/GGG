---
title: Get your Linting Checks here!
image: /images/ember.jpg
imageMeta:
  attribution: by The GatorGraderGirls
  attributionLink: https://unsplash.com/photos/OM4TjQwHC1I
featured: true
authors:
date: Fri Sept 13 2019 17:50:59 GMT+0100 (IST)

---

We love linting, yes we do, we love linting, how about you? Linting checks provide
a more structured and cohesive grading process than ever before. Professors will
not be able to say no!

**1. [confirmfileexists](#confirmfileexists)**<br>

**2. [countcommandoutput](#countcommandoutput)**<br>

**3. [countcommits](#countcommits)**<br>

**4. [countfilelines](#countfilelines)**<br>

**5. [countfileparagraphs](#countfileparagraphs)**<br>

**6. [countfilewords](#countfilewords)**<br>

**7. [countmarkdowntags](#countmarkdowntags)**<br>

**8. [countmultiplelinecomments](#countmultiplelinecomments)**<br>

**9. [countparagraphwords](#countparagraphwords)**<br>

**10. [countsinglelinecomments](#countsinglelinecomments)**<br>

**11. [executecommand](#executecommand)**<br>

**12. [listchecks](#listchecks)**<br>

**13. [matchcommandfragment](#matchcommandfragment)**<br>

**14. [matchcommandregex](#matchcommandregex)**<br>

**15. [matchfilefragment](#matchfilefragment)**<br>

**16. [matchfileregex](#matchfileregex)**<br>

## ConfirmFileExists
> Check Provided by GatorGrader: ConfirmFileExists<br>
> format: ConfirmFileExists [-h] --file FILE --directory DIR<br>
> optional arguments:<br>
>> -h, --help       show this help message and exit<br>
>
> required checker arguments:<br>
>
>> --file FILE      file for checking (default: None)<br>
>> --directory DIR  directory with file for checking (default: None)<br>

## CountCommandOutput
> Check Provided by GatorGrader: CountCommandOutput<br>
> format: CountCommandOutput [-h] --command COMMAND --count COUNT [--exact]<br>
> optional arguments:<br>
>> -h, --help         show this help message and exit<br>
>
> required checker arguments:<br>
>
>> --command COMMAND  command to execute (default: None)<br>
>> --count COUNT      how many of lines of output should exist (default: None)<br>
>
> optional check arguments:<br>
>
>> --exact            equals instead of a minimum number (default: False)<br>

## CountCommits
> Check Provided by GatorGrader: CountCommits<br>
> format: CountCommits [-h] --count COUNT [--exact]<br>
> optional arguments:<br>
>> -h, --help     show this help message and exit<br>
>
> required check arguments:<br>
>
>> --count COUNT  minimum number of git commits (default: None)<br>
>
> optional check arguments:<br>
>
>> --exact        equals instead of a minimum number (default: False)<br>

## CountFileLines
> Check Provided by GatorGrader: CountFileLines <br>
> format: CountFileLines [-h] --file FILE --directory DIR --count COUNT [--exact] <br>
> optional arguments: <br>
>>  -h, --help       show this help message and exit <br>
>
> required checker arguments:<br>
>
>> --file FILE      file for checking (default: None)<br>
>> --directory DIR  directory with file for checking (default: None)<br>
>> --count COUNT    how many lines should exist (default: None)<br>
>
> optional check arguments:<br>
>
>> --exact          equals instead of a minimum number (default: False)<br>

## CountFileParagraphs
> Check Provided by GatorGrader: CountFileParagraphs<br>
> format: CountFileParagraphs [-h] --file FILE --directory DIR --count COUNT [--exact]<br>
> optional arguments:<br>
>> -h, --help       show this help message and exit<br>
>
> required checker arguments:<br>
>
>> --file FILE      file for checking (default: None)<br>
>> --directory DIR  directory with file for checking (default: None)<br>
>> --count COUNT    how many paragraphs should exist (default: None)<br>
>
> optional check arguments:<br>
>
>> --exact          equals instead of a minimum number (default: False)<br>

## CountFileWords
> Check Provided by GatorGrader: CountFileWords<br>
> format: CountFileWords [-h] --file FILE --directory DIR --count COUNT [--exact]<br>
> optional arguments:<br>
>> -h, --help       show this help message and exit<br>
>
> required checker arguments:<br>
>
>> --file FILE      file for checking (default: None)<br>
>> --directory DIR  directory with file for checking (default: None)<br>
>> --count COUNT    how many total words should exist in the file (default:
                   None)<br>
>
> optional check arguments:<br>
>
>> --exact          equals instead of a minimum number (default: False)<br>

## CountMarkdownTags
> Check Provided by GatorGrader: CountMarkdownTags<br>
> format: CountMarkdownTags [-h] --tag TAG --file FILE --directory DIR --count COUNT [--exact]<br>
> optional arguments:<br>
>> -h, --help       show this help message and exit<br>
>
> required checker arguments:<br>
>
>> --tag TAG        markdown tag that exists in a file<br>
>> --file FILE      file for checking<br>
>> --directory DIR  directory with file for checking<br>
>> --count COUNT    how many tag instances should exist<br>
>
> optional check arguments:<br>
>
>> --exact          equals instead of a minimum number<br>
>> examples of available tags: code, code_block, heading, image, link, list, paragraph
>> markdown tag reference: https://spec.commonmark.org/0.29/<br>

## CountMultipleLineComments
> Check Provided by GatorGrader: CountMultipleLineComments<br>
> format: CountMultipleLineComments [-h] --file FILE --directory DIR --count COUNT [--language LANG]
[--exact]<br>
> optional arguments:<br>
>> -h, --help       show this help message and exit<br>
>
> required checker arguments:<br>
>
>> --file FILE      file for checking (default: None)<br>
>> --directory DIR  directory with file for checking (default: None)<br>
>> --count COUNT    how many multiple-line comments should exist (default:
                   None)<br>
>> --language LANG  language for the multiple-line comments (default: None)<br>
>
> optional check arguments:<br>
>
>> --exact          equals instead of a minimum number (default: False)<br>

## CountParagraphWords
> Check Provided by GatorGrader: CountParagraphWords<br>
> format: CountParagraphWords [-h] --file FILE --directory DIR --count COUNT [--exact]<br>
> optional arguments:<br>
>> -h, --help       show this help message and exit<br>
>
> required checker arguments:<br>
>
>> --file FILE      file for checking (default: None)<br>
>> --directory DIR  directory with file for checking (default: None)<br>
>> --count COUNT    how many words should exist in every paragraph (default:
                   None)<br>
>
> optional check arguments:<br>
>
>> --exact          equals instead of a minimum number (default: False)<br>

##CountSingleLineComments
> Check Provided by GatorGrader: CountSingleLineComments<br>
> format: CountSingleLineComments [-h] --file FILE --directory DIR --count COUNT [--language
{Java,Python}] [--exact]<br>
> optional arguments:<br>
>> -h, --help            show this help message and exit<br>
>
> required checker arguments:<br>
>
>> --file FILE           file for checking (default: None)<br>
>> --directory DIR       directory with file for checking (default: None)<br>
>> --count COUNT         how many single-line comments should exist (default:
                        None)<br>
>> --language {Java,Python}
                        language for the single-line comments (default: None)<br>
>
> optional check arguments:<br>
>
>> --exact               equals instead of a minimum number (default: False)<br>

## ExecuteCommand
> Check Provided by GatorGrader: ExecuteCommand<br>
> format: ExecuteCommand [-h] --command COMMAND<br>
> optional arguments:<br>
>> -h, --help         show this help message and exit<br>
>
> required checker arguments:<br>
>
>> --command COMMAND  command to execute (default: None)<br>

## ListChecks
> Check Provided by GatorGrader: ListChecks<br>
> format: ListChecks [-h] [--namecontains LABEL]<br>
> optional arguments:<br>
>> -h, --help            show this help message and exit<br>
>
> optional check arguments:<br>
>
>> --namecontains LABEL  filter by label that name must contain (default: None)<br>

## MatchCommandFragment
> Check Provided by GatorGrader: MatchCommandFragment<br>
> format: MatchCommandFragment [-h] --command CMD --fragment FRAG --count COUNT [--exact]<br>
> optional arguments:<br>
>> -h, --help       show this help message and exit<br>
>
> required checker arguments:<br>
>
  >> --command CMD    command to execute (default: None)<br>
  >> --fragment FRAG  fragment that exists in command output (default: None)<br>
  >> --count COUNT    how many of fragment should exist (default: None)<br>
>
> optional check arguments:<br>
>
>> --exact          equals instead of a minimum number (default: False)<br>

## MatchCommandRegex
> Check Provided by GatorGrader: MatchCommandRegex<br>
> format: MatchCommandRegex [-h] --command CMD --regex REGEX --count COUNT [--exact]<br>
> optional arguments:<br>
>> -h, --help     show this help message and exit<br>
>
> required checker arguments:<br>
>
>> --command CMD  command to execute (default: None)<br>
>> --regex REGEX  regular expression that matches command output (default:
                 None)<br>
>> --count COUNT  how many regex matches should exist (default: None)<br>
>
> optional check arguments:<br>
>
>> --exact        equals instead of a minimum number (default: False)<br>

## MatchFileFragmentS
> Check Provided by GatorGrader: MatchFileFragment<br>
> format: MatchFileFragment [-h] --file FILE --directory DIR --fragment FRAG --count COUNT [--exact]<br>
> optional arguments:<br>
>> -h, --help       show this help message and exit<br>
>
> required checker arguments:<br>
>
>> --file FILE      file for checking (default: None)<br>
>> --directory DIR  directory with file for checking (default: None)<br>
>> --fragment FRAG  fragment that exists in the file (default: None)<br>
>> --count COUNT    how many of a fragment should exist (default: None)<br>
>
> optional check arguments:<br>
>
>> --exact          equals instead of a minimum number (default: False)<br>

## MatchFileRegex
> Check Provided by GatorGrader: MatchFileRegex<br>
> format: MatchFileRegex [-h] --file FILE --directory DIR --regex REGEX --count COUNT [--exact]<br>
> optional arguments:<br>
>> -h, --help       show this help message and exit<br>
>
> required checker arguments:<br>
>
>> --file FILE      file for checking (default: None)<br>
>> --directory DIR  directory with file for checking (default: None)<br>
>> --regex REGEX    regular expression that matches file contents (default:
                   None)<br>
>> --count COUNT    how many regex matches should exist (default: None)<br>
>
> optional check arguments:<br>
>
>> --exact          equals instead of a minimum number (default: False)<br>
