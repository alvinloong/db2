# [Database fundamentals](https://www.ibm.com/support/knowledgecenter/en/SSEPGG_9.7.0/com.ibm.db2.luw.container.doc/doc/c0052964.html)

## [SQL](https://www.ibm.com/support/knowledgecenter/en/SSEPGG_9.7.0/com.ibm.db2.luw.sql.ref.doc/doc/c0004100.html)

### [Functions](https://www.ibm.com/support/knowledgecenter/en/SSEPGG_9.7.0/com.ibm.db2.luw.sql.ref.doc/doc/c0006211.html)

#### [Scalar functions](https://www.ibm.com/support/knowledgecenter/en/SSEPGG_9.7.0/com.ibm.db2.luw.sql.ref.doc/doc/c0000767.html)

##### [TRIM](https://www.ibm.com/support/knowledgecenter/en/SSEPGG_9.7.0/com.ibm.db2.luw.sql.ref.doc/doc/r0023198.html)

```
SELECT TRIM(:HELLO),
 TRIM(TRAILING FROM :HELLO)
FROM SYSIBM.SYSDUMMY1;
SELECT TRIM(L '0' FROM :BALANCE),
FROM SYSIBM.SYSDUMMY1;
```

### [Catalog views](https://www.ibm.com/support/knowledgecenter/en/SSEPGG_9.7.0/com.ibm.db2.luw.sql.ref.doc/doc/r0008443.html)

#### [SYSCAT.DATATYPES](https://www.ibm.com/support/knowledgecenter/en/SSEPGG_9.7.0/com.ibm.db2.luw.sql.ref.doc/doc/r0001040.html)

#### [SYSCAT.SEQUENCES](https://www.ibm.com/support/knowledgecenter/en/SSEPGG_9.7.0/com.ibm.db2.luw.sql.ref.doc/doc/r0004203.html)

#### [SYSCAT.TRIGGERS](https://www.ibm.com/support/knowledgecenter/en/SSEPGG_9.7.0/com.ibm.db2.luw.sql.ref.doc/doc/r0001066.html)

