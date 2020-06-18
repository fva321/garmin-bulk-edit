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
