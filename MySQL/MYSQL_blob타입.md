# MYSQL

```xml
<!-- 필드명 수정시 AS 사용 -->
cast(CBM_CONTENTS as varchar(10000)) AS CBM_CONTENTS
```

```xml
<!-- Blob 타입 select 시 -->
cast(CBM_CONTENTS as varchar(10000)) AS CBM_CONTENTS

<!-- 또는 -->
convert(CBM_CONTENTS USING UTF8) from CBM_CONTENTS;

```