import time
from plyer import notification

if __name__ == "__main__":
    while True:
        notification.notify(
            title = "Please drink water now!!",
            message = "If you don't drink enough water each day, you risk becoming dehydrated. Warning signs of dehydration include weakness, low blood pressure, dizziness, confusion, or urine that's dark in color.",
            app_icon = "E:\Minor Project\icon.ico",
            timeout = 12           #The message will be displayed for 12 seconds
    )
    time.sleep(30*60)     #Turns the notification ON after every 30 minutes