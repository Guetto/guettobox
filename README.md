edbox
=====

edbox.color = "#fff";
edbox.applyBlock('.div-fieldset-box-complete');
edbox.applyBlock('.checkbox-div-mon-refs');
edbox.alertBox({
	element: "body",
	type: 'error',
	titulo: 'Itiner�rio Atual',
	texto: 'Deseja deletar o itiner�rio atual?',
	cancel: function(){
		edbox.closeBlock('body');
	},
	confirm: function(){
		
	}
});
