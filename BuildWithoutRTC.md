**Issue**  
Without RTC battery odroid doesn't remember the time. So after restart the following message appears when running make:

**Solution**  
Give all the files the current time with:  
find /directory -type f -exec touch {} +
