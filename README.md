# PreLab3-OSG

![image](https://github.com/user-attachments/assets/4ca75b90-9268-4909-b484-816db71b897c)

---

![image](https://github.com/user-attachments/assets/bb1bbecc-db3b-4391-974f-d481c89c499c)

---
![image](https://github.com/user-attachments/assets/d49be5e9-2d31-4766-af55-9c22d9e12e6f)

---
![image](https://github.com/user-attachments/assets/5e1c2f7d-5386-4ba2-813f-2a040cde2895)
* E: DEVNAME=/dev/sda1 -> phân vùng
* E: DEVTYPE=partition -> loại thiết bị (phân vùng)
* E: MAJOR=8 -> số chính, dại diện trình điều khiển (driver) -> sata và scsi = 8
* E: MINOR=1 -> số phụ  , dùng để phân biệt phân vùng. sẽ thường là số Y trong /dev/sdXY
* E: SUBSYSTEM=block -> block device
* E: ID_BUS=scsi -> giao tiếp (scsi / sata)

---
![image](https://github.com/user-attachments/assets/463a600c-d219-4592-a4e5-e6d8b23f02fc)

![image](https://github.com/user-attachments/assets/38b92034-77d1-4bf2-9d80-2b9748405f3e)

![image](https://github.com/user-attachments/assets/2ffff92e-1dd1-44b4-9ed8-ad4c50981cb8)

-   **`command > /dev/null`**: Discard standard output.
-   **`command 2> /dev/null`**: Discard error messages.
-   **`command > /dev/null 2>&1`**: Discard both output and error messages.
-   **`command < /dev/null`**: Run a command without any input.
