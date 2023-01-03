# HTML

select 유효성 검사 참고

```xml
<!-- select문 유효성 검사 참고 -->
<select class="form-control input-sm" name="bomCategory" title="카테고리" data-validation='{ "required" : true }'>
	<option value="">선택</option>
	<option value="1">카테고리명1</option>
	<option value="2">카테고리명2</option>
	<option value="3">카테고리명3</option>
	<c:forEach items="${Category }" var="row">
		<option value="${row.Id }" ${row.Nm == boardDetail.CategoryNm ? 'selected="selected"' : '' }>${row.Nm }</option>
	</c:forEach>
</select>
```