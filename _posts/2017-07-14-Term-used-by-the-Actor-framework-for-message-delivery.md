---
layout: post
title: Actor 프레임워크의 메시지 전달에서 사용하는 용어
published: true
categories: [Network]
tags: network actor
--- 
- at-most-once delivery는 메커니즘에 건네지는 각 메시지에 대해 해당 메시지가 0 번 또는 1 번 전달됨을 의미합니다. 보다 일반적인 용어로는 메시지가 손실 될 수 있음을 의미합니다.  
  
<br>
    
- at-least-once(최소한 한 번 전달) 메커니즘에 전달 된 각 메시지에 대해 전달할 때 잠재적으로 여러 번의 시도가 이루어 지므로 적어도 하나는 성공합니다. 다시 말하면, 좀 더 일반적인 용어로 이것은 메시지가 중복 될 수는 있지만 없어지지는 않는다는 것을 의미합니다.  
  
<br>
    
- exactly-once(정확히 한 번 전달)은 메커니즘에 전달 된 각 메시지에 대해 수신자에게 정확히 한 번 전송된다는 것을 의미합니다. 메시지는 손실되거나 중복 될 수 없습니다.  
  