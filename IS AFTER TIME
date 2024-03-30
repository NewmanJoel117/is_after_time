def print_time(time):
    print('The time is: %.2d:%.2d:%.2d' % (time.hour, time.minute, time.second))

# Now, let's pretend we have a Time object with some values
class Time:
    def __init__(self, hour, minute, second):
        self.hour = hour
        self.minute = minute
        self.second = second

# We create a Time object with some values
my_time = Time(9, 30, 5)

# And now we can use our function to print the time
print_time(my_time)




def is_after(t1, t2):
    # We're going to compare the hours first
    if t1.hour > t2.hour:
        return True
    elif t1.hour == t2.hour:
        # If the hours are the same, we check the minutes
        if t1.minute > t2.minute:
            return True
        elif t1.minute == t2.minute:
            # If the minutes are the same, we check the seconds
            if t1.second > t2.second:
                return True
    # If none of the above conditions are met, it means t1 doesn't come after t2
    return False

# Now let's use our function with some Time objects
time1 = Time(10, 30, 15)
time2 = Time(9, 45, 10)

# Let's see if time1 comes after time2
result = is_after(time1, time2)
print('Does time1 come after time2?', result)
