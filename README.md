# Recognition-of-incomplete-number-plates-of-vehicles

In recent years, the rise in unauthorized vehicles using fake or forged number plates has become a significant concern for law enforcement agencies, private security, and public safety. Criminals often employ deceptive tactics by using counterfeit plates to evade identification, making it challenging to track and apprehend them. To address this growing issue, the development of advanced technologies, particularly in the field of computer vision and machine learning, has paved the way for effective fake number plate detection systems.

# Solution
- STEP 1: First identify the model of the vehicle and the number plate details which might be an incomplete one. The details should consist of the company and the color of the vehicle.
- STEP 2: Once the model of the vehicle has been identified, the known digits of the license plate are compared with the database of license plate numbers for that specific type of model.
- STEP 3: If the known digits match a license plate number in the database, then the complete license plate number can be determined.
- STEP 4: If the known digits do not match any license plate numbers in the database, then the incomplete license plate number can only be determined with more data.

# Process of implementation
- Collecting dataset
- Extracting the color
- Extracting the logo
- Extracting the registration number
- Comparing extracted data with the dataset
 
