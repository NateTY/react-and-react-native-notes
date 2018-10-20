mapDispatchToProps
-------------
  如果是 function, 將 dispatch 當參數 invoke 後，取得回傳的 object, 每個  property 都是 props func
  如果是 object, 每個 property 都是 props func

dispatch 的參數
-------------
  如果是 function, 將 dispatch 當參數 invoke, 取得 return, 直到不是 function, 就當作 action, 才使用
  如果是 action, 直接使用
