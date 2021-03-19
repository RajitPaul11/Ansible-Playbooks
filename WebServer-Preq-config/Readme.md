<b><u>Complete Apache WebServer Setup along with making the service module idempotent</u></b>
<br /><img src="https://syslint.com/wp-content/uploads/2019/04/Installing-Apache-in-Remote-hosts-Using-Ansible-Playbook.jpg" alt="ansibleandapachehttpd">
<ul>
  <li>Directory Created using file module</li>
  <li>ISO File mounted on the dir using mount module</li>
  <li>Yum Repos Configured using yum_repository module</li>
  <li>httpd package installed using package module</li>
  <li>Web Content copied to Document root of httpd</li>
  <li>Output of Copy task registered in x</li>
  <li>Var x output using debug module</li>
  <li>Restarting httpd service only if web-content is updated</li>
  <li>Attaching the when clause to service module and making it idempotent</li>
  <li>Creating a rule for httpd in firewall using the firewalld module</li>
  <li>Displaying the ip address of the managed node using the Ansible Facts</li>
 </ul>
