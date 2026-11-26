# Positions in CSS

## Note:

postion which considering the document flow, we can plan an element.

### there are 5 positions in CSS

1. static position is the default document position
   it means the below doesn't change anything

- top
- bottom
- left
- right

2. position: relative
   - it respects the document flow
   - it is relative to its old postion
     it means: top: 100px, = it means it pushes 100px from top side of its old location

3. position absolute

- it is relative to the nearest parent
- the parent contanier => postion: relative;
- the child container => postion: absolute;

4. position fixed

- it doesn't respect the document flow
- it relatives to the view port

5. position sticky
