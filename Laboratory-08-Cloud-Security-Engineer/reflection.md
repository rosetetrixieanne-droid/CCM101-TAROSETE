
# Mission Reflection: Cloud Security Engineer

## 1. How does a host-based firewall protect a server even if the physical network perimeter is breached?

A host-based firewall protects a server by controlling incoming and outgoing network traffic directly on the machine. Even if an attacker passes through the network's main security defenses, the firewall can still block unauthorized connections to the server. By allowing only trusted and necessary services, it adds another layer of protection against possible attacks.

## 2. Why is managing open network ports critical to reducing a server's attack surface?

Managing open network ports is important because every open port can provide a possible entry point for attackers. If unnecessary ports remain open, attackers may discover running services and attempt to exploit their vulnerabilities. By allowing only required ports, such as SSH for administration and port 8080 for the web application, we can reduce the attack surface and improve server security.

## 3. Why is it dangerous to leave a database port like 3306 for MySQL open to the public internet?

Leaving MySQL port 3306 open to the public internet is dangerous because unauthorized users may attempt to access the database, guess passwords, or exploit security vulnerabilities. If an attacker gains access, sensitive information such as customer records, usernames, and passwords could be exposed, modified, or deleted. In an enterprise environment, database access should be restricted to trusted servers and authorized users.

## 4. What did I learn from this mission?

This mission taught me that securing a server requires more than deploying an application. I learned how to run an Nginx container using Docker, configure UFW, set a Default Deny policy, and allow specific network ports. I also realized that a small configuration mistake can expose a server to security risks. Testing commands and checking firewall rules are important steps in protecting a system.

## 5. How does my GitHub portfolio look after completing eight missions?

After completing eight missions, my GitHub portfolio shows my progress in learning cloud computing, server deployment, monitoring, and security. Each laboratory activity helped me develop practical technical skills and improve my documentation. I understand that cloud security is a continuous responsibility, and I will continue practicing these skills to become a better IT professional.
