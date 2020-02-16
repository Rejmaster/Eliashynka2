# Info o `config.json`

## Skąd wziąć template do `config.json`

Template można wziąć z `config.json.EXAMPLE`. Wystarczy usunąć `.EXAMPLE` z nazwy. 


## Jakie wartości wpisać do `config.json`

* `token` - token do bota. Można go otrzymać tworząc aplikację na [panelu developerskim Discorda](https://discordapp.com/developers/applications)
* `prefix` - znak (bądź kilka) którymi chcemy zaczynać komendy.
* `logChannel` - ID specjalnego kanału, na który będą wysyłane wszelkie błędy bądź informacje z bota.
* `ownerID` - ID osoby hostującej bota, czyli najprawdobniej twoje.
* `supporterRoles` - tablica z ID ról które otrzymują osoby które wspierają serwer. Dobrym przykładem jest takiej roli jest Nitro Booster.
* `supporterRolesPos` - pozycja **od dołu listy**, na której mają być dodawane role z kolorami, jeżeli osoba kwalifikuje się na otrzymanie roli z kolorem. Zaleca się wpisanie pozycji nad wszystkimi rolami, które mogą nadpisać kolor.

# 🇬🇧 Info about `config.json`

## How to get a `config.json` template

You can obtain the template from `config.json.EXAMPLE`. Just remove the `.EXAMPLE` part.

## What values should I fill into `config.json`?

* `token` - the bot's token. You can get yours by creating an app on [Discord's developer panel](https://discordapp.com/developers/applications)
* `prefix` - a symbol (or symbols) that you want to begin the commands with.
* `logChannel` - the ID of a special channel, that all error reports and info will be sent.
* `ownerID` - the ID of the person who's hosting the bot.
* `supporterRoles` - an array with IDs of roles that support the server. A good example of such role is Nitro Booster.
* `supporterRolesPos` - the position **from the bottom of the role list** on which the color roles will be added. It's recommended that this position should be higher than any of roles that can override the color.