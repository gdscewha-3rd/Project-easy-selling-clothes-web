## Code Description
### π category_classification.ipynb
μ·μ μ’λ₯λ₯Ό λΆλ₯νλ AI  
- code : data preprocessing, model training, inference
- train input : (35518, 100, 100, 3)
- inference input : (1, 100, 100, 3) (λ°°μΉ λ¨μλ‘ μλ ₯νκ² μ½λ λ³κ²½λ κ°λ₯)
- inference output : (1, 4)
    - label  
    0: μμ°ν°  
    1: νμ   
    2: μνΌμ€  
    3: μμ  

### π style_classification.ipynb
μ·μ μ€νμΌμ λΆλ₯νλ AI  
- code : data preprocessing, model training, inference
- train input : (35518, 100, 100, 3)
- inference input : (1, 100, 100, 3) (λ°°μΉ λ¨μλ‘ μλ ₯νκ² μ½λ λ³κ²½λ κ°λ₯)
- inference output : (1, 9)
    - label  
    0: λ νΈλ‘  
    1: λ‘λ§¨ν±   
    2: λ§€λμ  
    3: λͺ¨λ  
    4: λ°λ¦¬ν°λ¦¬  
    5: μΉμ  
    6: μ€ν¬ν°  
    7: νλ―Έλ  
    8: νλ νΌ  

### π initial_code.ipynb
μ¬λ¬κ°μ§ μλ λ° μμ΄λμ΄ code

<br></br>

## Improvement
- κ° μ΄λ―Έμ§ μ¬μ΄μ¦μ λ§μΆ° μ μ²λ¦¬νκΈ°(νμ¬λ λ©λͺ¨λ¦¬λΆμ‘±)
- λ λ§μ λ°μ΄ν°λ‘ νμ΅
- μ»€μ€ν λͺ¨λΈ λ§λ€κΈ°
- hyperparameter μ‘°μ 
