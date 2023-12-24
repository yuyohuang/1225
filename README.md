class Course:
    def __init__(self, course_code, course_name, credit_hours, mandatory, instructor, class_time):
        self.course_code = course_code
        self.course_name = course_name
        self.credit_hours = credit_hours
        self.mandatory = mandatory
        self.instructor = instructor
        self.class_time = class_time

    def display_info(self):
        print(f"課程代碼: {self.course_code}")
        print(f"課程名稱: {self.course_name}")
        print(f"學分數: {self.credit_hours}")
        print(f"必選修: {self.mandatory}")
        print(f"任課老師: {self.instructor}")
        print(f"上課時間: {self.class_time}")
        print()

# 建立物件
course1 = Course("C001", "程式設計基礎", 3, "必修", "王老師", "星期一 10:00-12:00")
course2 = Course("C002", "資料結構與演算法", 3, "選修", "林老師", "星期三 14:00-16:00")
course3 = Course("C003", "資料庫管理系統", 3, "必修", "張老師", "星期五 08:00-10:00")

# 顯示課程資訊
course1.display_info()
course2.display_info()
course3.display_info()
