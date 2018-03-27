
# DatabaseBuilder

Use Spring EmbeddedDatabaseBuilder to set up embedded derby database

    EmbeddedDatabaseBuilder builder = new EmbeddedDatabaseBuilder();
    EmbeddedDatabase db = builder.setType(EmbeddedDatabaseType.DERBY).addScript("ddl-setup-script.sql").build();
        
    JdbcTemplate jdbc = new JdbcTemplate(db);
    // run tests against the database . . .
    
    db.shutdown();


