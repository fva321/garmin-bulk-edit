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

## Example

```
.../search/activities?limit=200&start=200&activityType=cycling
```

### Credits
All credit belong to `BunBun!` from the `Garmin Forum: Bulk change of privacy settings for past activities`

Source: https://forums.garmin.com/apps-software/mobile-apps-web/f/garmin-connect-web/107758/bulk-change-of-privacy-settings-for-past-activities/847543#
