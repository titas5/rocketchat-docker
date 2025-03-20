# rocketchat-docker


# Check ownership and permissions of the directory
ls -ld ./mongodb_data

# If necessary, change ownership to allow Docker to write to the directory
sudo chown -R 1001:1001 ./mongodb_data
