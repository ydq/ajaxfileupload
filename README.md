# ajaxfileupload
ajaxfileupload


	<input type="file" id="file_input_id" name="myfiles"/>

	$.ajaxFileUpload({
		url: '/uploadurl',
		fileElementId:'file_input_id',
		data:{key:'value'},//data
		dataType:'json',
		success:function(data, status){
			//upload success
		},
		error: function (data, status, e) {
			//error
		}
	})
