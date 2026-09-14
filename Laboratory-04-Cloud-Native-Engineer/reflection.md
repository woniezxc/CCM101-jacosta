# Mission Reflection

Docker containers start almost instantly compared to Virtual Machines because they do not need to boot a complete operating system kernel. A VM virtualizes full hardware and loads a dedicated Guest OS, which takes minutes. Containers share the host operating system kernel and isolate processes, allowing them to boot in seconds.

Port mapping (`-p 8080:80`) is necessary because containers run in isolated network environments by default. Binding port 8080 on the host machine to port 80 inside the container allows external traffic sent to the host's IP address to reach the web server inside the container.

When executing the `docker rm` command, the container instance and its top writable layer are permanently deleted. Any files or data stored inside that specific container layer that were not saved to a persistent volume will be lost.

Containerization improves DevOps collaboration by providing consistent software environments. Developers can package an application and its dependencies into a single image, eliminating environment mismatch issues ("it works on my machine") when passing code to IT operations for deployment.

My GitHub Cloud Computing Portfolio is developing into a complete showcase of cloud skills. Moving from basic system concepts to hands-on container operations demonstrates practical skills in modern infrastructure management.
