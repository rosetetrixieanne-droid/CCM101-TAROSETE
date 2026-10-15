# Firewall Configuration

## 1. Allow SSH

Command:

    sudo ufw allow ssh

Purpose: This command allows SSH connections for
remote server administration.

## 2. Configure Default Policies

Commands:

    sudo ufw default deny incoming
    sudo ufw default allow outgoing

Purpose: Incoming connections are blocked by default,
while outgoing connections are allowed.

## 3. Enable UFW

Command:

    sudo ufw enable

## 4. Allow Port 8080

Command:

    sudo ufw allow 8080/tcp

Purpose: This allows TCP traffic to the web
application on port 8080.

## 5. Verify Firewall Rules

Commands:

    sudo ufw status verbose
    sudo ufw status numbered

## 6. Security Warning

If UFW is enabled before allowing SSH, remote
administrators may lose SSH access because incoming
SSH connections can be blocked by the firewall.
