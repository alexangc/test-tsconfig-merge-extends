In the [official docs](https://www.typescriptlang.org/tsconfig/#extends), the
`extends` property from `tsconfig.json` is supposed to be a string. But it seems
an array of strings works as well 🤷‍♂️

Eventually I found out [this
issue](https://github.com/tsconfig/bases/issues/148) showing that this is indeed
a feature, and not an undefined behaviour.
