BACKEND LOGIC FOR ALBUM CLASS

MOCK DATABASE: We'll be adding mock databases as @@class variables in #hash format, so some methods inside Album class will be specific to hashes

READ: .all() returns all the results from our db. 
  `def self.all
    @@albums.values()
  end`

CREATE: .save() saves an new album with `Album.new('name', #{id})` We can pass the id as nil so 