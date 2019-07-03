# Flutter Push Notification Example

What it contains?

  - Register Push Token
  - Receive Push Message
    - onMessage
    - onResume
    - onLaunch
    
**How to send notification from CURL ?**
`
DATA='{"notification": {"body": "this is a body","title": "this is a title"}, "priority": "high", "data": {"click_action": "FLUTTER_NOTIFICATION_CLICK", "id": "1", "status": "done"}, "to": "FCM_TOKEN"}'
curl https://fcm.googleapis.com/fcm/send -H "Content-Type:application/json" -X POST -d "$DATA" -H "Authorization: key=SERVER_KEY"
`

Complete Instruction: [Flutter Push Notification Tutorial [with VIDEO]](https://codesundar.com/flutter-push-notification/)
