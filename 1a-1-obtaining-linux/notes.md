Lab 1a-1 Reflection questions

Q1 : What challenges did i you encounter during the virtual machine setup? 
I was using a MACBOOK with a M2 chip so i had to stray away from using the normal VMWARE or Virtualbox we were recommended to use however i quickly understood the setup process
i came across this challenge where when installing "whois" it turned out to be my VM's clock that was off so the package list looked like it was coming from the future so the apt refused them
resulting in me not being able to reach the servers.
so i ran: 

--------------------------------------------------
sudo timedatectl set-ntp false
sudo timedatectl set-time "2026-11-12 11:20:00"
timedatectl

sudo apt update
sudo apt install whois

--------------------------------------------------

This resulted in the problem being solved. |

Q2 : What did you learn about virtualization tools and their differences? 
I learned that virtualization runs the guest OS that was built for the same CPU as the host which results in it being fast because the guest is using a real CPU
since i was using UTM it offers both virtualization and emulation and its FREE!!! while other tools like parallels are paid but are more polished and has better intergration and better suited to apple silicon

Q3 : How confident do you feel using Ubuntu after completing this lab? 
Honestly i am still not the most confident as there are still alot i need to familiarize myself with and i need to get used to using the terminal to navigate and not constantly checking the "commands cheat sheet" but i do have 
a strong understanding of how to install linux now and i am going to try doing so on other platforms like windows

Q4 : In what ways can a virtualised linux enviroment help in the industry scenario? 
It allows Admins and Devs to try updates, configs or any risky changes in a VM first. If it breaks, they can just roll back to a snapshot.
VM's are safe places to test and make mistakes without causing any real major damage to software, applications.
It is also cost efficient as one server can run multiple VMs at a time 

Q5 : What would you have done differently if setting up another VM? 
I would plan to try to add more resources to my VM and make sure i have my time sync'd so i can avoid the headache of not knowing why it cant reach the servers to install the packages i need.


screenshots





