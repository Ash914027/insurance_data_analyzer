

# Problem Statement 🤔

Medical Insurance has become a part of the common man's life given the time of pandemic we are living in. The data that we have helps analysts allocate suitable policy to a valued customer. Data cleaning is a major part before any analysis can be performed.

In this challenge, you need to read the data from a CSV(Comma Separated Value) file that is insurance.csv file filter the required data to write it another file.

The dataset​..

- age: age of primary beneficiary​
- sex: insurance contractor gender, female, male​
- bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9​
- children: Number of children covered by health insurance / Number of dependents​
- smoker: Smoking​
- region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest​
- charges: Individual medical costs billed by health insurance

# Tasks 📋
- Read the CSV file line by line that contains data of the insurance record.​
- Filter all the records for female candidates given region as southwest.​
- Write all the filtered data in file 'femaleRegion.txt'.
- Read the same csv file using Streams.​
- Filter all the records for male or female with no children.​
- Write all the filtered data in 'noChildren.txt'.

# Instructions 🛠️

1. Download and unzip the boilerplate code.
2. Run the command npm install to install the dependencies.
3. Open the boilerplate code in VSCode to develop the assignment solution.
4. Write the logic in **.js** file present in **src** folder
5. Read the **.csv** file given in resources folder
6. Run the test scripts available under src/test by giving the npm run test command in the terminal to test locally.
7. Refactor the solution to ensure all test cases are passing.
8. Zip the solution code with the name same as the assignment name.
9. Upload the zipped solution for submission.
