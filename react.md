Add new element to the array stored in state

```
let newPage = [{ subject: 'InitialMeetingName' }]


setMeetings([...meetings, newMeeting]);
setMeetings([...newPage, ...meetings]);

```

Update one property
```
 setUser({ ...user, [name]: value })

```

Use effect
- when elements in array will change then function will be changed
- empty array will invoke method only on load
```
useEffect(() => {
    setWorkingEvent({ ...meeting });
},[]);
```
