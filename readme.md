# My personal GitHub Notification app

This is an app based off of the jQuery TodoMVC example. It has been altered to display my own GitHub notifications.

## Description

The goal of this app is just to work with GitHub's API and to sync up with my own notifications. By checking off a notification on this app, it also marks the notification as "read" on GitHub. In addition, any new GitHub notifications, read or unread will be updated on this app.

The majority of this ass has been kept in it's original form. Only a GitHub object was created to enclose additional functions that is used to interact with GitHub's API. These additional functions includes:

`getNotifications()`: Gets all the notifications.
`storeNotifications(data)`: Store notifications from AJAX into localStorage.
`markRead(todo)`: Mark as read locally.
`markReadOnGitHub(data)`: Mark as read on GitHub.

## References

As mentioned, this app is based off of the jQuery TodoMVC which could be found [here](http://todomvc.com/).

## License

MIT
