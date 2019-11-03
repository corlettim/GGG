---
title: Get your Automated Checks here!
image: /images/ember.jpg
imageMeta:
  attribution: by The GatorGraderGirls
  attributionLink: https://unsplash.com/photos/OM4TjQwHC1I
featured: true
authors:
date: Fri Sept 13 2019 17:50:59 GMT+0100 (IST)

---

The GatorGrader automated checks provide a more structured and cohesive grading
process than ever before. Professors will not be able to say no! While we have
a definite 14 automated checks, instructors will be able to create their own
automated checks that will represent a plug-in basis.

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

**12. [matchcommandfragment](#matchcommandfragment)**<br>

**13. [matchcommandregex](#matchcommandregex)**<br>

**14. [matchfilefragment](#matchfilefragment)**<br>

**14. [matchfileregex](#matchfileregex)**<br>

## ConfirmFileExists
> Check Provided by GatorGrader: ConfirmFileExists<br>
> Format: ConfirmFileExists [-h] --file FILE --directory DIR<br>
> Example: ConfirmFileExists <br>

## CountCommandOutput
> Check Provided by GatorGrader: CountCommandOutput<br>
> Format: CountCommandOutput [-h] --command COMMAND --count COUNT [--exact]<br>
> Example: CountCommandOutput --command "gradle -q --console plain run" --count 4 --exact <br>

## CountCommits
> Check Provided by GatorGrader: CountCommits<br>
> Format: CountCommits [-h] --count COUNT [--exact]<br>
> Example: CountCommits --count 10<br>

## CountFileLines
> Check Provided by GatorGrader: CountFileLines <br>
> Format: CountFileLines [-h] --file FILE --directory DIR --count COUNT [--exact] [--reach]<br>
> Example: CountFileLines --count 100<br>

## CountFileParagraphs
> Check Provided by GatorGrader: CountFileParagraphs<br>
> Format: CountFileParagraphs [-h] --file FILE --directory DIR --count COUNT [--exact]<br>
> Example: CountFileParagraphs --count 7<br>

## CountFileWords
> Check Provided by GatorGrader: CountFileWords<br>
> Format: CountFileWords [-h] --file FILE --directory DIR --count COUNT [--exact] [--reach]<br>
> Example: CountFileWords --count 300<br>

## CountMarkdownTags
> Check Provided by GatorGrader: CountMarkdownTags<br>
> Format: CountMarkdownTags [-h] --tag TAG --file FILE --directory DIR --count COUNT [--exact]<br>
> Example: CountMarkdownTags --tag "heading" --count 6 --exact<br>

## CountMultipleLineComments
> Check Provided by GatorGrader: CountMultipleLineComments<br>
> Format: CountMultipleLineComments [-h] --file FILE --directory DIR --count COUNT [--language LANG]
[--exact] [--reach]<br>
> Example: CountMultipleLineComments --language Java --count 2<br>

## CountParagraphWords
> Check Provided by GatorGrader: CountParagraphWords<br>
> Format: CountParagraphWords [-h] --file FILE --directory DIR --count COUNT [--exact]<br>
> Example: CountParagraphWords --count 100<br>

##CountSingleLineComments
> Check Provided by GatorGrader: CountSingleLineComments<br>
> Format: CountSingleLineComments [-h] --file FILE --directory DIR --count COUNT [--language
{Java,Python}] [--exact] [--reach]<br>
> Example: CountSingleLineComments --language Java --count 2<br>

## ExecuteCommand
> Check Provided by GatorGrader: ExecuteCommand<br>
> Format: ExecuteCommand [-h] --command COMMAND<br>
> Example: ExecuteCommand --command "gradle build"<br>

## MatchCommandFragment
> Check Provided by GatorGrader: MatchCommandFragment<br>
> Format: MatchCommandFragment [-h] --command CMD --fragment FRAG --count COUNT [--exact]<br>
> Example: MatchCommandFragment --command "htmlhint src/www/index.html" --fragment "no errors found" --count 1 --exact<br>

## MatchCommandRegex
> Check Provided by GatorGrader: MatchCommandRegex<br>
> Format: MatchCommandRegex [-h] --command CMD --regex REGEX --count COUNT [--exact]<br>
> Example: MatchCommandRegex --command "gradle -q --console plain run" --count 1 --regex "Hello\s+\w+\.(\n)Gradle(\s+\w+)*\.(\n)Docker(\s+\w+)*\." --exact<br>

## MatchFileFragment
> Check Provided by GatorGrader: MatchFileFragment<br>
> Format: MatchFileFragment [-h] --file FILE --directory DIR --fragment FRAG --count COUNT [--exact] [--reach]<br>
> Example: MatchFileFragment --fragment "TODO" --count 0 --exact<br>

## MatchFileRegex
> Check Provided by GatorGrader: MatchFileRegex<br>
> Format: MatchFileRegex [-h] --file FILE --directory DIR --regex REGEX --count COUNT [--exact]<br>
> Example: MatchFileRegex --regex "Hello\s+\w+\.(\n)Gradle(\s+\w+)*\.(\n)Docker(\s+\w+)*\." --count 2
