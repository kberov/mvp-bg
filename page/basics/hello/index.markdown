Кодът:

    #!/usr/bin/env perl
    use strict;
    use warnings;
    
    print "hello world\n";

Как се пуска:

    $ perl hello.pl
    hello world

#### strict и warnings

Лоша практика е да не използвате
([use](https://perldoc.perl.org/functions/use.html))
[strict](https://perldoc.perl.org/strict.html) и
[warnings](https://perldoc.perl.org/warnings.html) навсякъде в програмите си.

- `use strict` прави така, че използването на някои изрази да се смятат за грешки.
- `use warnings` включва допълнителни предупреждения при някои изрази.

И двата израза целят да предотвратят използването на стар лош синтаксис, който
интерпретаторът на Perl приема като правилен, но най-вероятно ще допусне
непредвидено поведение на вашия код и грешки, които са много трудни за
откриване.

