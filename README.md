# Database

### Tạo Database tại SQLServer
- Sau khi tạo Database chạy file `database.sql` trong SQL Server.
- Đổi tên của Database tại biến `databaseName` ở file `src\main\main\java\com\evaluation\source\config\DataSourcecConfig.java`.
```
dataSource.setUrl("jdbc:sqlserver://localhost:1433;databaseName=250924;encrypt=true;trustServerCertificate=true;");
```

# Backend

- Chạy Service: 
```
mvn spring-boot:run
```

# Frontend
- Tải package:
```
npm install
```
- Chạy Service:
```
npm start
```
