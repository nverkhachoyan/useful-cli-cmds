# Create a symbolic link
ln -s path_to_existing_directory name_of_symbolic_link

# Omit -s to create hard link
ln path_to_existing_directory name_of_symbolic_link

# Remove existing link and create new (force)
ln -sf path_to_existing_directory name_of_symbolic_link
