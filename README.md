# score_detection

Link dataset: https://github.com/ai-in-actiune/evaluari_scolare


YOLOv5_score_detection_training - notebook for network training
    
    

YOLOv5_score_predict_gradio - API for score detection
    
    For prediction of score you need to:
        - upload best.pt
        - run Init and Prediction cell 

    getLstSplitImg  - return (list of array) split detected object from row image
    getCoordsScore  - return (dict) with 6 keys: 'x0'- list of coordinates of point x0 from row image
                                                 'y0'- list of coordinates of point y0 from row image
                                                 'x1'- list of coordinates of point x1 from row image
                                                 'y1'- list of coordinates of point y1 from row image
                                                 'percent_cls'- list of percentage of localized score
                                                 'isEmpty' - False if was found a score object
    
    class Yolov5ScoreLocalization - class of optimized yolov5.detect model, 

best.pt - trained weights, for score localization
