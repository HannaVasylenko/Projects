# Members block
<br><br>
![Website image](/assets/members.png)


### 1. Request <span style="color:#22DD22;">_GET_</span> members with name "hanna" by search.

![Image](/assets/Members/getbyname_memb.png)

![Image](/assets/Members/getbynamet_memb.png)
<br><br>

### 2. Request <span style="color:#22DD22;">_GET_</span> members with name "nonexistent" by search, negative verification.

![Image](/assets/Members/getbyname_neg_memb.png)

![Image](/assets/Members/getbynamet_neg_memb.png)
<br><br>

### 3. Request <span style="color:#22DD22;">_GET_</span> members on page "10".

![Image](/assets/Members/getbypage_memb.png)

![Image](/assets/Members/getbypaget_memb.png)
<br><br>

### 4. Request <span style="color:#22DD22;">_GET_</span> member by ID.

![Image](/assets/Members/getbyid_memb.png)

![Image](/assets/Members/getbyidt_memb.png)
<br><br>

### 4. Request <span style="color:#FFBF00;">_POST_</span> add member with symbols in name "Api !@#$%& Doe". This verification is implemented only on the front end

![Image](/assets/Members/postwithsymbt_memb.png)

![Image](/assets/Members/postwithsymb_memb.png)
<br><br>

### 5. Request <span style="color:#FFBF00;">_POST_</span> create member with valid data.

![Image](/assets/Members/post_memb.png)

![Image](/assets/Members/postt_memb.png)
<br><br>

### 6. Request <span style="color:#A020F0;">_PATCH_</span> update member with symbols in name "Upd !@#$%& Doe". The test should fail. The verification is implemented only on the front end.

![Image](/assets/Members/updwithsymb_memb.png)

![Image](/assets/Members/updwithsymbt_memb.png)
<br><br>

### 7. Request <span style="color:#A020F0;">_PATCH_</span> update member.

![Image](/assets/Members/upd_memb.png)

![Image](/assets/Members/updt_memb.png)
<br><br>

### 7. Request <span style="color:#FF0000;">_DELETE_</span> delete member.

![Image](/assets/Members/del_memb.png)

![Image](/assets/Members/delt_memb.png)

> Verify that a member with a certain ID is not in the database.

![Image](/assets/Members/getbyidtaf_memb.png)