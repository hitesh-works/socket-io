>> server side events- 
- connection
- disconnect
- message 
- reconnect 
- ping 
- join
- leave

>> client side events-
- connection
- connect_error
- connect_timeout
- reconnect

io.on - is used to catch any events
emit() - is usually used to create custom events
         .emit("eventName", data)

io.sockets.emit("broadcast", { message: users + " users connected" });
-- we use this when we want to send to all 

rooms - means channels
