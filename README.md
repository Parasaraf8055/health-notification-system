# health-notification-system
health notification system by using python <br>
from plyer import notification
import time
if __name__ == "__main__":
    notification.notify(
        title = "PLEASE DRINK WATER",
        message = "drinking 4 to 5 litres of water every day keep you hydrated",
        timeout = 10
    )
    time.sleep(2*60)
    
if __name__ == "__main__":
    notification.notify(
        title = "TIME FOR EXERCISE",
        message = "every day exercise keep doctors way",
        timeout = 5
    )
    time.sleep(3*60)    
