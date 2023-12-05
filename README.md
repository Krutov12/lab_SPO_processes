# lab_SPO_processes

<img width="191" alt="image" src="https://github.com/Krutov12/lab_SPO_processes/assets/77206997/a35a9b79-d102-4254-b843-78f0b12a034a">

Разница между restart и reload заключается в том, что restart полностью перезапускает службу, в то время как reload перезагружает конфигурацию службы, не прерывая ее работу. В большинстве случаев reload предпочтительнее, поскольку не вызывает перерыв в обслуживании

<img width="316" alt="image" src="https://github.com/Krutov12/lab_SPO_processes/assets/77206997/90bc93f2-47a7-48ad-bbd6-d760db2efd67">

ps aux | grep mc

<img width="960" alt="image" src="https://github.com/Krutov12/lab_SPO_processes/assets/77206997/4d798135-1064-47f4-9535-50d5f47da5ad">

sudo kill -9 

<img width="960" alt="image" src="https://github.com/Krutov12/lab_SPO_processes/assets/77206997/ae3e47cf-d62f-410e-bb2b-b5fb800ba223">

[Unit]
Description=Ping localhost as userping

[Service]
Type=simple
ExecStart=/bin/ping -c 4 127.0.0.1

[Install]
WantedBy=default.target


<img width="362" alt="image" src="https://github.com/Krutov12/lab_SPO_processes/assets/77206997/ba7279c0-aa23-4e0a-88f6-0561fe175958">

top -p 

<img width="474" alt="image" src="https://github.com/Krutov12/lab_SPO_processes/assets/77206997/3db988d8-2758-4e01-9e46-744dc6a5678d">
