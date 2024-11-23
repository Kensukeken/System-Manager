# System Manager Project
![](/assets/systemManager.png)
## Description
This project is a Java application that manages a list of systems, including laptops, phones, and servers. It allows users to create, retrieve, and delete system records. Each system record includes attributes such as ID, type, location city, model, serial number, and purchase date.

## Components
1. **`SystemRecord` Class**: An abstract base class that stores common attributes for all system types.
2. **`Laptop`, `Phone`, and `Server` Classes**: Subclasses of `SystemRecord` that store additional attributes specific to each system type.
3. **`SystemManager` Class**: Manages the list of system records, providing methods to add, retrieve, and delete records.
4. **`Main` Class**: Provides a command-line interface for interacting with the user to perform operations on the system records.

## Usage
1. **Creation**: Allows the user to create a new system record by specifying the type (Laptop, Phone, or Server) and other relevant details.
2. **Retrieval**: Allows the user to retrieve a system record by its ID.
3. **Deletion**: Allows the user to delete a system record by its ID.
4. **Exit**: Exits the application.

## Example
### Example Data
- **ID**: 58BFA38FMN84DK34
- **Type**: Laptop
- **Location City**: Windsor
- **Model**: Lenovo ThinkPad T14
- **Serial**: ALKSV98234
- **Purchase Date**: 2023-10-14
- **Has LTE Module**: Yes

### Example Output
```
Welcome to the System Manager!
Please select your choice (1-4):
1) Creation
2) Retrieval
3) Deletion
4) Exit

Enter Type (Laptop/Phone/Server): Laptop
Enter Location City: Windsor
Enter Model: Lenovo ThinkPad T14
Enter Serial: ALKSV98234
Enter Purchase Date (YYYY-MM-DD): 2023-10-14
Has LTE Module (yes/no): yes
System created successfully!

Enter ID to retrieve: 58BFA38FMN84DK34
ID: 58BFA38FMN84DK34
Type: Laptop
Location City: Windsor
Model: Lenovo ThinkPad T14
Serial: ALKSV98234
Purchase Date: 2023-10-14
Has LTE Module: Yes
```

## Requirements
- Java 17
- IntelliJ IDEA 2024.3

## Setup
1. Clone the repository `https://github.com/Kensukeken/System-Manager.git`.
2. Open the project in IntelliJ IDEA.
3. Ensure the project SDK is set to Java 17.
4. Run the `Main` class to start the application.

## Author
- Kensukeken