# regex_isolating_sentences
 Regex to isolate sentences ended by full stop

I was analyzing a book and I had wondered if I could isolate sentences with a regex.

It's not beautiful, but it gave me what I wanted at the time.

The syntax is compatible with the Boost C++ regex library, used by Notepad++.

```
(?<!SEC)(?<!Jos)(?<!Ltd)(?<!Ret)(?<!Mass)(?<!Inv)(?<!Cont)(?<!Qtr)(?<!Ref)(?<! )(?<!Mid)(?<!Prod)(?<!Mfg)(?<!Cos)(?<!Inc)(?<!Indus)(?<!Intl)(?<!Telecomm)(?<!\([A-Z])(?<!^Am)(?<!Tel)(?<!Elec)(?<!Cen)(?<!Ill)(?<!Lt)(?<!Pwr)(?<!Div)(?!<El)(?!<Svs)(?!<Sou)(?!<Calif)(?<!Jan)(?<!Feb)(?<!Mar)(?<!Apr)(?<!Jun)(?<!Jul)(?<!Aug)(?<!Sept)(?<!Oct)(?<!Nov)(?<!Dec)(?<!M R )(?<!Mr)(?<!Ms)(?<!Mrs)(?<!^Nor)(?<!Nor\. Pac)(?<!^[A-Z])(?<! vol)(?<! no)(?<! vs)(?<!\(p)(?<![A-Z]\.[A-Z])(?<! [A-Z])(?<![0-9])(?<!Corp)(?<!Co)(?<![Ee]d)(?<![Pp]p)(?<! \. )\.(?! \. )((|”|”|”|”\*|\))( )?)
```

Enjoy :)
