# FFXIV Triggernometry Trigger

## The Epic of Alexander Nisi Partner Callout
- Should works straightaway
- Trigger will detect your Final Judgement Nisi and Check who is your partner is
- First Partner Callout timing is around when you attack CC's Plasma Shield (12s after getting Final Judgement Debuff)
- Second Partner Callout timing is around when you need to stackup behind the ice (30s after getting Final Judgement Debuff)

### There's two sceneario in this section (3rd Passing)

#### You have Nisi Debuff
- If you have Nisi Debuff on your self 
- (Eg. Delta, You need to send Delta to Partnet who have Final Judgement Delta)
- ACT will call "Send Beta to (Your Partnet Name)"

#### You don't have Nisi Debuff
- If you don't Nisi Debuff on your self 
- (Eg. Your Final Judgement Debuff is Delta , You need to get Delta from someone)
- ACT will call "Get Delta from (Your Partner Name)"

### 4th passing will callout after 3rd water is resolved
- It will call which debuff you need to get and who are your partner
- (Eg. Your Final Judgement Debuff is Alpha , You need to stack with your partner at specfic location behind ice)
- ACT will call "Stack with Alpha (Your Partner Name)"
- ACT will call "Stack with Alpha You" If you didn't get the first cycle debuff
