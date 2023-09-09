# Fork the Saleor platform repository
1. Access the repository at https://github.com/saleor/saleor-platform and copy the HTTPS link
<img width="722" alt="Screenshot 2023-09-09 at 1 15 16 PM" src="https://github.com/lbj-jj/isec6000-assignment1-task2/assets/61398620/901db5fa-6dbe-46a7-a7ac-124b9783aa3e">
2. Fork the Saleor platform repository
   a. Open terminal on Virtual Machine
   b. Install Git on Ubuntu by running the commands:
sudo apt-get update
sudo apt-get install git
   c. Fork the Saleor platform repository by running the command:
···Bash
git clone + "the HTTPS link copying in step 1"
```

# Run a Saleor stack
Follow the step-by-step guidelines outlined in the Saleor platform repository to run a Saleor stack enriched with sample data effectively

# Tailor the Compose file and verify the successful launch
1. Edit the docker-compose.yaml to change the dashboard port from 9000 to 9003
   <img width="486" alt="Screenshot 2023-09-09 at 1 48 54 PM" src="https://github.com/lbj-jj/isec6000-assignment1-task2/assets/61398620/7fd3758a-6d67-4c45-8234-18f335568444">

3. login to localhost:9003 to login the platform
   <img width="822" alt="Screenshot 2023-09-08 at 11 41 49 PM" src="https://github.com/lbj-jj/isec6000-assignment1-task2/assets/61398620/77e27ca1-65a5-4902-92ca-6c4521f1f1d9">
   
# Commit modifications and push them to the forked repository
1. Under the directory saleor-platform, click "Add file" -> "Upload files"
<img width="771" alt="Screenshot 2023-09-09 at 1 42 41 PM" src="https://github.com/lbj-jj/isec6000-assignment1-task2/assets/61398620/2a21da24-0b4e-4ed6-b471-ba663cc88869">
2. Drag the modified file docker-compose.yaml to the designed area and click the "commit changes" button
<img width="962" alt="Screenshot 2023-09-09 at 1 46 44 PM" src="https://github.com/lbj-jj/isec6000-assignment1-task2/assets/61398620/261bd1da-45bb-4bdc-a3ad-4cd8f19a93a1">
3. The change will be updated immediately

<img width="470" alt="Screenshot 2023-09-09 at 1 48 35 PM" src="https://github.com/lbj-jj/isec6000-assignment1-task2/assets/61398620/54fe8551-9d39-48da-abe4-8acd368915ec">
