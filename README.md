spring-data-jpa-examples
========================

JPA : (Java Persistence API)

Definition:
  Wrapped Hibernate/JDO/ ... .
  Support Mysql/Oracle/Postgres ...
  Total Object relational
  
Example:
  POJO denfinition , annotation based, include (@Column, @Entity, @Table ... ) and mapped object
  Repository denfinition
    extends JpaRepository 
  
  Naming Search
    by field
    support and, or , isnull, notnull, like 
    support range(between), ge, le ...  first , top
    support page, sort
    support related objects search 
    
    by @Query
    support hsql  using object 
    support native sql
    
  @Trsactional
    trsaction management support, naturly support
    
  Dynamic Search
    using specification (critira build)
    using EntityManager create query
  
  
  
  QueryDsl integration .....
