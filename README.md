# AirBnB Clone Project

This project focuses on the implementation of the back-end console of the AirBnB
clone
# Classes:

AirBnB Clone utilizes the following classes:
### BaseModel 
FileStorage User State City Amenity Place Review

### Public Instance Attributes
id created_at updated_at

### Public Instance Method 
save to_dict all new save reload

### Public Class Attributs 
email password first_name last_name name state_id city_id user_id description number_of_rooms number_of_bathrooms max_guest price_by_night latitude longitude amenity_ids place_id uder_id text

### Private Class Attributes
file_path objects

# How Does it work?

The above classes are handle, the by the abstracted storage engine defined in the FileStorage class.
When the backend is intialized, AirBnB instantiates an instance of FileStorage called storage. The Storage object is loaded from any class instance stored in the JSON file file.json. Each time class instances are created, deleted or updated, the storage object is used register corresponding changes in the file.json.

Console: The console is a command line interpreter that permits management of the backen of AirBnB. It can be used to handle and manipulate all classes utilized by the application. This is achieved by calls on the storage object defined above.

