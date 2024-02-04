=================================ALL USER==============

SELECT 'CREATE OR REPLACE SYNONYM ' ||USER_NAME||'.LOAN_BAL_MNYR_MRA_SAMITY_TYPE FOR LOAN_BAL_MNYR_MRA_SAMITY_TYPE;'FROM  V$USER
CREATE OR REPLACE SYNONYM HOPEAPX.PKG_VW_PARAM FOR PKG_VW_PARAM; 
=====table=====
grant select update delete  on table to user
==========================
procedure/ function ///grant execute on (procedure/funcati) to user ()
grant execute on PKG_VW_PARAM to MIS_OFFICER;
grant execute on PKG_VW_PARAM to HO_AUDIT_OFFICER;
