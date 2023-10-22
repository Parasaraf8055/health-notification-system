# health-notification-system
health notification system by using python <br>
from plyer import notification<br>
import time <br>
if __name__ == "__main__": <br>
    notification.notify( <br>
        title = "PLEASE DRINK WATER", <br>
        message = "drinking 4 to 5 litres of water every day keep you hydrated", <br>
        timeout = 10 <br>
    ) <br>
    time.sleep(2*60) <br>
    
if __name__ == "__main__": <br>
    notification.notify( <br>
        title = "TIME FOR EXERCISE", <br>
        message = "every day exercise keep doctors way", <br>
        timeout = 5 <br>
    ) <br>
    time.sleep(3*60) <br>    
