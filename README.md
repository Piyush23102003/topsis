# TOPSIS
Full stack project for topsis score calculation

# Topsis score
When you provide the whole information such as file,email,weights etc. then you receive a email and also a link will be displayed at your screen from where you can download the file.

# Cloudinary
i have use this as database to store the answers.csv file

# Nodemailer
it is used to send the email to the receipent or the user.


# Flow of project

1. It inputs the csv file,weights,email and impacts from user
2. It asks user whether to drop first column or not (as the first column of data contains unique id such as roll no., name etc.)
3. It parses the csv data of the file and matches the dimensions of the file and the inputtes weights and targets
4. If all is correct it apply topsis on it and generates a output file
5. After it, output file goes on cloudinary and generates a secure url for user.
6. After the whole process file is shared at email address provided by the user and also link is shown up to screen to download it 
