Permission
    Manager 
        -Dashboard
        -ManageStock
        -ManageProduct
        -RegisterEmployee
    Employee
        -Sale
        -receipt


/backend
    /data 
        -ProductData เก็บข้อมูลผลิตภัณฑ์
        -InMemoryStore เก็บประวัติการซื้อขาย
    /models
        /Products
            -Product กำหนดลักษณะผลิตภัณฑ์
        /Users
            -Employee กำหนดลักษณะพนักงาน
            -User กำหนดลักษณะผู้ใช้
        /services
            -AuthService ควบคุมการล็อกอิน จัดการผู้ใช้
            -InventoryService ดึงข้อมูลผลิตภัณฑ์
            -SalesService ควบคุมการขาย ประวัติ
            -DashboardService ควบคุมแดชบอร์ด
/Client
    /Component เก็บพวกส่วนประกอบ เช่น การ์ดผลิตภัณฑ์
    /User เก็บหน้าล็อกอิน สมัคร
    -MainFrame หน้าหลัก
/resources 
    -Tools เก็บเครื่องมือที่ใช้บ่อย
    -SetPreferences ตั้งค่า


    
