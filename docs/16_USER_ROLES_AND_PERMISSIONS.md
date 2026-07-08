# 16 - User Roles and Permissions

## 1. Overview

يحدد هذا المستند نظام المستخدمين والصلاحيات في منصة سنا الرقمية لضمان إدارة آمنة ومنظمة للوصول إلى البيانات والوظائف.

يعتمد النظام على:

- Role Based Access Control (RBAC)
- Permission Management
- Access Policies
- Audit Tracking

---

## 2. User Types

تتكون المنصة من أنواع المستخدمين التالية:

- System Administrator
- Clinic Manager
- Doctor
- Receptionist
- Patient
- Support User

---

## 3. System Administrator

الصلاحيات:

- إدارة النظام بالكامل.
- إدارة المستخدمين والأدوار.
- إعدادات الأمان.
- مراقبة النشاطات.
- إدارة التكاملات.

---

## 4. Clinic Manager

الصلاحيات:

- إدارة بيانات المركز.
- إدارة الموظفين.
- متابعة التقارير.
- إدارة الجداول.
- مراجعة الأداء التشغيلي.

---

## 5. Doctor Role

الصلاحيات:

- عرض ملفات المرضى المصرح بها.
- إنشاء وتحديث السجلات الطبية.
- إضافة التشخيصات والملاحظات.
- متابعة المواعيد.
- إصدار التقارير الطبية.

---

## 6. Receptionist Role

الصلاحيات:

- تسجيل المرضى.
- حجز وتعديل المواعيد.
- إدارة قائمة الانتظار.
- استقبال المدفوعات.

لا يملك صلاحية:

- تعديل البيانات الطبية الحساسة.

---

## 7. Patient Role

الصلاحيات:

- إنشاء الحساب.
- إدارة الملف الشخصي.
- حجز المواعيد.
- الاطلاع على السجل المسموح.
- استقبال الإشعارات.

---

## 8. Permission Matrix

| Feature | Admin | Manager | Doctor | Reception | Patient |
|---|---|---|---|---|---|
| User Management | ✓ | ✓ | - | - | - |
| Appointments | ✓ | ✓ | ✓ | ✓ | ✓ |
| Medical Records | ✓ | - | ✓ | - | Limited |
| Reports | ✓ | ✓ | ✓ | Limited | - |
| Settings | ✓ | Limited | - | - | - |

---

## 9. Access Control Rules

- مبدأ أقل صلاحية ممكنة.
- فصل الصلاحيات الطبية والإدارية.
- تسجيل العمليات الحساسة.
- مراجعة الصلاحيات بشكل دوري.

---

## 10. Audit Logging

يتم تسجيل:

- تسجيل الدخول.
- تعديل البيانات.
- عرض الملفات الطبية.
- تغيير الصلاحيات.
- العمليات الإدارية.

---

## 11. Security Considerations

- Multi Factor Authentication عند الحاجة.
- Session Management.
- Token Based Authentication.
- Encryption للبيانات الحساسة.

---

## 12. Future Expansion

دعم أدوار مستقبلية:

- Laboratory Staff
- Pharmacy Staff
- Insurance Provider
- External Healthcare Partner

