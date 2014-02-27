cheatCode.js
============

Create your own cheat code pattern with keys and hand gestures.


Example:

                var secretPattern = new cheatCode();
                secretPattern.setCode({ target: 'body',
                                        type:'gesture', 
                                        code: ['up','up','down','down','left','right','left','right','tap','tap','tap'],
                                        interval: 3,
                                        success: function(){
                                                alert("Secret code unlock.");
                                        }
                });
