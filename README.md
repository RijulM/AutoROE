# AutoROE

An external network assessment tool to prevent mistyped scans 1) violating Rules of Engagement 2) attacking benign IPs 

I provide no guarantee it's in a fully functional state/will prevent launching accidental attacks. That said, just chmod +x and enjoy.

Future goals:

-IPv6 integration

-Internal Testing functionality

-Automation options, maybe crontab integration for duration of testing

**Note: Automatic IP detection currently uses "hostname -I" without looping. Ensure appropriate network configuration or decline option. This tool is still focused on external testing.
