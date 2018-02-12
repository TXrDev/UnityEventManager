# UnityEventManager

### Just for demo purpose. ###

@ EventManagerSimple
Ability to add/remove listeners to specific string event.

EventManager.StartListening("MyEvent", handler);  
EventManager.TriggerEvent("MyEvent");  
void Handler() {}  
EventManager.StopListening("MyEvent", handler);  

@ EventManager
Base + pass game object as an event data.

EventManager.StartListeningGo("MyEvent", handler);  
EventManager.TriggerEventGo("MyEvent", gameObject);  
void Handler(GameObject go) {}  
EventManager.StopListeningGo("MyEvent", handler);  
