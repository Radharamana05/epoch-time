# epoch-time
# python program to know the epoch time.
from datetime import*
now=datetime.now()
print(now)
today=date.today()
day=today.day
month=today.month
year=today.year
hour=now.hour
minute=now.minute
second=now.second
print(f"current date:{{{day}-{month}-{year}}}")
print(f"current Time:{{{hour}:{minute}:{second}}}")

# output
2024-06-17 11:03:44.733645
current date:{17-6-2024}
current Time:{11:3:44}
