import time
from plyer import notification

if __name__ == "__main__":
  while True:
    notification.notify(
      title = "Please do a back stretch!!",
      message = "Reducing tension in muscles supporting the spine; tension in these muscles can worsen pain from any number of back pain conditions",
      timeout=5
    )
    time.sleep(60*60)
