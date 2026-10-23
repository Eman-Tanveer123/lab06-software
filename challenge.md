# Challenge: Install It Yourself

### 1. Install htop, run it, and write one thing it shows
- **Command:** `sudo apt install -y htop` and `htop`
- **Answer:** It shows real-time system process management, CPU usage, memory (RAM) usage, and running tasks.

### 2. Which version of apache2 does Ubuntu offer?
- **Command:** `apt show apache2`
- **Answer:** Version 2.4.x (e.g., 2.4.58-1ubuntu8)

### 3. How many packages are installed on your server now?
- **Command:** `apt list --installed | wc -l`
- **Answer:** Checked via `apt list --installed | wc -l` (Total packages count displayed on terminal).

### 4. Use Docker to run alpine container
- **Command:** `sudo docker run --rm alpine echo "Hello from Alpine"`
- **Answer:** Output displayed `Hello from Alpine`.

### 5. Full path of Docker's key file and sources file
- **Command:** `ls /etc/apt/keyrings/docker.asc` and `ls /etc/apt/sources.list.d/docker.sources`
- **Answer:**
  - Key File: `/etc/apt/keyrings/docker.asc`
  - Sources File: `/etc/apt/sources.list.d/docker.sources`

### 6. Remove htop and prove it is gone
- **Command:** `sudo apt remove -y htop` followed by `hash -r` and `htop`
- **Answer:** Running `htop` returns `Command 'htop' not found`.
