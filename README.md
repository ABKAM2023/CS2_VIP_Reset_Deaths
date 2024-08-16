**[VIP] Reset Deaths** - добавляет возможность VIP-игрокам сбрасывать количество своих смертей с помощью команд `!rd` или через VIP меню с командой `!vip`.

В `groups.ini` добавьте следующее:
```
  "ResetDeaths" "1"  // Установите значение "1", чтобы разрешить сброс смертей
```

В файл `vip.phrases.txt` добавьте следующее:
```
	"ResetDeaths"
	{
		"en"    "Reset deaths"
		"ru"    "Сброс смертей"
	}
	"deaths_reset"
	{
		"en"    "Deaths have been reset."
		"ru"    "Счётчик смертей сброшен."
	}
	"deaths_already_zero"
	{
		"en"    "Your death count is already zero."
		"ru"    "У вас уже ноль смертей."
	}
```

**Требования:**
[VIP CORE](https://csdevs.net/resources/vip-core.511/)
