# ajaxfileupload
ajaxfileupload

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
