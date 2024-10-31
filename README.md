# SPEEDTEST CLI
Kiểm tra tốc độ VPS bằng Speedtest CLI
<h2>Cài đặt Speedtest CLI</h2>
<h3>Redhat</h3>
<blockquote>curl -s https://packagecloud.io/install/repositories/ookla/speedtest-cli/script.rpm.sh | sudo bash<br>
sudo yum install speedtest</blockquote>
<h3>Debian / Ubuntu </h3>
<blockquote>sudo apt-get install curl
curl -s https://packagecloud.io/install/repositories/ookla/speedtest-cli/script.deb.sh | sudo bash
sudo apt-get install speedtest</blockquote>
<h2>Yêu cầu</h2>
<p>Mở port 8080</p>
<h2>Kiểm tra</h2>
<p>chạy lệnh sau:</p>
<blockquote>speedtest --server-id={ID}</blockquote>
<h2>Danh sách ID </h2>
<ul>
  <li>HCM - "VIETPN CO, LTD": 11342</li>
  <li>HCM - "CMC TELECOM": 10577</li>
  <li>HCM - "Viettel": 9994</li>
  <li>HCM - "VNPT-NET": 6106</li>
  <li>HCM - "FPT Telecom": 2515</li>
</ul>
<p>Xem thêm tại: https://gist.github.com/ofou/654efe67e173a6bff5c64ba26c09d058</p>
