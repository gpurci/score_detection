# score_detection

Link dataset: https://github.com/ai-in-actiune/evaluari_scolare


YOLOv5_score_detection_training - notebook pentru antrenare si descarcarea modelelor antrenate
    
    

YOLOv5_score_predict_gradio - API for score detection
    
    For prediction of score you need to:
        - upload best.pt
        - model.zip
        - run all cells           
        - 

    get_img_from_location   - (list of array) split detected object from row image
    get_object_localization - (str)object localization
    
    score_clasifier         - (str)predict detected object
    predict_score           - (str)predict scores and sum of scores from row image, 

best.pt - model antrenat pentru detectarea obiectelor ce reprezinta punctajul pentru fiecare exercitiu

model.zip - model antrenat pentru clasificarea punctajelor 
