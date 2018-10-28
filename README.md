## Following installation steps

- https://rnfirebase.io/docs/v5.x.x/installation/initial-setup

- https://rnfirebase.io/docs/v5.x.x/installation/android

- https://rnfirebase.io/docs/v5.x.x/messaging/android

- https://rnfirebase.io/docs/v5.x.x/notifications/android

## Send notification request example for api

### Path(POST): https://fcm.googleapis.com/fcm/send

    + Headers

            {
                "Content-Type": "application/json",
                "Authorization": "key=AAAA39to........"
            }


    + Content
    
            {
                "to": "****", 
                "notification":{
                    "title": "Simple FCM Client",
                    "body": "This is a notification with only NOTIFICATION.",
                    "sound": "default"
                },
                "priority": 10
            }

### Request detail: https://firebase.google.com/docs/cloud-messaging/http-server-ref
