# garmin-bulk-edit

## Type Key Settings

```
typeKey: private, subscribers, groups, public
```

## Parameters

```
?limit= number of activities to change, starting from latest
&start= start from nth+1 activity, counting from latest
&activityType= running, cycling, fitness_equipment, walking, other
&startDate= YEAR-MM-DD
&endDate= YEAR-MM-DD
&minDistance= in meters
&maxDistance= in meters
```

##### Example

```
.../search/activities?limit=200&start=200&activityType=cycling
```

## Credits
All credit belong to `BunBun!` from the `Garmin Forum: Bulk change of privacy settings for past activities`

> As you got it working, it's good.
>
> Anyway it's also possible to use similar script in web-browser console (F12 key), so here is my script, tested in Firefox. Edit the search link to filter activities you want to change - and change typeKey to privacy level you need.
>
> Below it's limit=1 for testing if it works as wanted, it will change only first latest activity to private.
>
> It's normal search link from Connect Web, so it accepts all filters visible on the website, if you need more filters just check them on the website and add them by &.

##### Source
https://forums.garmin.com/apps-software/mobile-apps-web/f/garmin-connect-web/107758/bulk-change-of-privacy-settings-for-past-activities/847543
