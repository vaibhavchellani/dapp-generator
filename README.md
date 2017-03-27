### Keys

A generator to scaffold Ethereum Dapps.

```bash
npm install -g yo
```

To install generator-ethdapp from npm, run:

```bash
npm install -g generator-ethdapp
```

Finally, initiate the generator:

```bash
yo ethdapp
```

== Generating your Dapp

For a generic Dapp:
```bash
yo ethdapp
```

For a Dapp taylored to Parity:
```bash
yo ethdapp:parity
```

Then answer the questions. Once you are done, run the deploy script:
```bash
./deploy.sh
```

Then (re)start Parity:
```bash
parity ui
```

You will see your app listed there:

image:images/parity.png[]

Click on that link and you will see your DAPP:

image:images/generated.png[]


== License

MIT
