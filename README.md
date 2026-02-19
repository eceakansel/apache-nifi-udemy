# apache-nifi-udemy

# Navigate to your project root
cd ~/apache_nifi

# Ensure the source and target directories exist
mkdir -p source target

# Create a sample transaction file in the source folder
echo "tx_id,amount,status
101,500.00,SUCCESS
102,150.50,PENDING" > source/tx_sample.csv
