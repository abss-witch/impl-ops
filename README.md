# impl-ops
Custom derive macros to implement component wise opperations.
```
use impl_ops::CmpOps;
#[derive(CmpOps)]
pub struct Point{
    a: f32,
    b: i8,
    c: i16
}
```