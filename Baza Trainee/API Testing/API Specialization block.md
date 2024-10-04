# Specialization block
<br><br>
![Website image](/assets/spec.png)

### 1. Request <span style="color:#22DD22;">_GET_</span> specializations with name "quality" by search.

![Image](/assets/Specialization/getbyname_spec.png)

![Image](/assets/Specialization/getbynamet_spec.png)
<br><br>

### 2. Request <span style="color:#22DD22;">_GET_</span> specializations with name "nonexistent" by search, negative verification.

![Image](/assets/Specialization/getbyname_neg_spec.png)

![Image](/assets/Specialization/getbynamet_neg_spec.png)
<br><br>

### 3. Request <span style="color:#22DD22;">_GET_</span> specializations on page "1".

![Image](/assets/Specialization/getbypage_spec.png)

![Image](/assets/Specialization/getbypaget_spec.png)
<br><br>

### 4. Request <span style="color:#22DD22;">_GET_</span> specialization by ID.

![Image](/assets/Specialization/getbyid_spec.png)

![Image](/assets/Specialization/getbyidt_spec.png)
<br><br>

### 4. Request <span style="color:#FFBF00;">_POST_</span> add specialization with symbols in name "Api !@#$%& en". This verification is implemented only on the front end

![Image](/assets/Specialization/postwithsymb_spec.png)

![Image](/assets/Specialization/postwithsymbt_spec.png)
<br><br>

### 5. Request <span style="color:#FFBF00;">_POST_</span> create specialization with valid data.

![Image](/assets/Specialization/post_spec.png)

![Image](/assets/Specialization/postt_spec.png)
<br><br>

### 6. Request <span style="color:#A020F0;">_PATCH_</span> update specialization with symbols in name "Upd Api !@#$%& en". The test should fail. The verification is implemented only on the front end.

![Image](/assets/Specialization/updwithsymb_spec.png)

![Image](/assets/Specialization/updwithsymbt_spec.png)
<br><br>

### 7. Request <span style="color:#A020F0;">_PATCH_</span> update specialization.

![Image](/assets/Specialization/upd_spec.png)

![Image](/assets/Specialization/updt_spec.png)
<br><br>

### 7. Request <span style="color:#FF0000;">_DELETE_</span> delete specialization.

![Image](/assets/Specialization/del_spec.png)

![Image](/assets/Specialization/delt_spec.png)

> Verify that a specialization with a certain ID is not in the database.

![Image](/assets/Specialization/getbyidtaf_spec.png)