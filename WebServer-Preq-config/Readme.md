<b><u><h3>Complete Apache WebServer Setup along with making the service module idempotent</h3></u></b>
<br />
<br /><img src="https://syslint.com/wp-content/uploads/2019/04/Installing-Apache-in-Remote-hosts-Using-Ansible-Playbook.jpg" alt="ansibleandapachehttpd">
<ul>
  <li>Directory Created using file module</li>
  <p>- Creating a directory on the Managed Node to mount the ISO file</p>
  <li>ISO File mounted on the dir using mount module</li>
  <p>- Mounting the ISO image onto the directory created on the MN</p>
  <li>Yum Repos Configured using yum_repository module</li>
  <p>- Configuring AppStream and BaseOS Repo</p>
  <li>httpd package installed using package module</li>
  <p>- Installing Apache httpd package </p>
  <li>Web Content copied to Document root of httpd</li>
  <p>- Copied index.html to /var/www/html</p>
  <li>Output of Copy task registered in x</li>
  <p>- Used register to store the output of copy play</p>
  <li>Var x output using debug module</li>
  <p>Output of copy play displayed on the screen</p>
  <li>Restarting httpd service only if web-content is updated</li>
  <p>- Service to be restarted only when copy play is run</p>
 <li>Attaching the when clause to service module and making it idempotent</li>
  <p>- Turning the service module idempotent</p>
  <li>Creating a rule for httpd in firewall using the firewalld module</li>
  <p>Creating a rule for the default httpd port - Port 80</p>
  <li>Displaying the ip address of the managed node using the Ansible Facts</li>
  <p>MN Ip displayed on screen</p>
 </ul>
