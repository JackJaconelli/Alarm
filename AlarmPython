import webbrowser
import schedule
import time

def open_and_play_youtube():
    youtube_link = 'https://www.youtube.com/watch?v=W8MratH51eY'
    webbrowser.open(youtube_link, new=2) 

alarm_time = '05:00'

schedule.every().day.at(alarm_time).do(open_and_play_youtube)

while True:
    schedule.run_pending()
    time.sleep(1)
 
