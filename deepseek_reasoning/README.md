openai deepseek 思考  

~/go/pkg/mod/github.com/sashabaranov/go-openai@v1.32.2/chat.go  
增加  
ReasoningContent any    `json:"reasoning_content,omitempty"`  

火山引擎增加deepseek 思考  
https://github.com/volcengine/volcengine-go-sdk/blob/v1.0.181/service/arkruntime/model/chat_completion.go  
ReasoningContent *string                       `json:"reasoning_content,omitempty"`  
