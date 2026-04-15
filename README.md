# task-2-basic-firewall-configuration-with-ufw
**UFW (Uncomplicated Firewall)** is a simple command-line tool used to manage and configure firewall rules on Linux systems.
Here’s a clean and ready-to-use README file for **Task 2: Basic Firewall Configuration with UFW**:

---

#  Task 2: Basic Firewall Configuration with UFW

##  Objective

To configure and manage a basic firewall using **UFW (Uncomplicated Firewall)** to control incoming and outgoing network traffic on a Linux system.

---

##  Requirements

* Ubuntu / Debian-based Linux system
* Root or sudo privileges
* Internet connection

---

##  Installation of UFW

1.sudo apt update

2.sudo apt install -y ufw

3.sudo ufw allow ssh   

4. sudo ufw deny http

5.sudo ufw enable 

6. sudo ufw status verbose

##  Conclusion

UFW provides a simple yet powerful way to manage firewall rules on Linux systems. By configuring basic allow/deny rules, you can significantly improve system security.

---

## References

* Official UFW Documentation: [https://help.ubuntu.com/community/UFW](https://help.ubuntu.com/community/UFW)


