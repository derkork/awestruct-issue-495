This demonstrates issue 495 (https://github.com/awestruct/awestruct/issues/495) of awestruct.

Run

```
rake update
rake gen[prod]
```

to see the error. If you change the awestruct version in the `Gemfile` from the github version to 0.5.6 and again  do

```
rake update
rake gen[prod]
```

the error goes away.