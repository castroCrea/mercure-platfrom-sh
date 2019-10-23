# Platform SH With Mercure Implementation

## Use full command line
### Install Platform SH on your bash
```curl -sS https://platform.sh/cli/installer | php```

### Check the log
```platform log```

### check the env variables
```platform variables -e master```

### Push to platform 
```git push -u platform master ```

### Get the url where
```platform url```

## config on PS
Add 2 env variables

* env:MERCURE_SECRET
* env:MERCURE_PUBLISH_ALLOWED_ORIGINS

## Info 
We use a S size check why here https://github.com/dunglas/mercure/blob/master/docs/hub/load-test.md

## Warning ⚠️
Remove DEMO=1 Parameters from `web.commands.start`

All explanation https://github.com/dunglas/mercure/blob/master/docs/hub/config.md