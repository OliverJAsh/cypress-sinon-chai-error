# cypress-sinon-chai-error

#### Steps to reproduce

```bash
# no errors
tsc

yarn add cypress
# errors! (see below)
tsc
```

#### Example output

```sh-session
$ tsc
node_modules/@types/sinon-chai/index.d.ts:107:31 - error TS2694: Namespace 'Chai' has no exported member 'ChaiPlugin'.

107 declare const sinonChai: Chai.ChaiPlugin;
                                  ~~~~~~~~~~


Found 1 error.
```