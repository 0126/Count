# Count
//  Created by Yoshiki Kishimoto on 2018/04/04.
//  Copyright © 2018年 Yoshiki Kishimoto. All rights reserved.
//

import UIKit

class ViewController: UIViewController {
    
    var number: Int = 0
    @IBOutlet var label: UILabel!
    
    override func viewDidLoad() {
        super.viewDidLoad()
        // Do any additional setup after loading the view, typically from a nib.
    }

    override func didReceiveMemoryWarning() {
        super.didReceiveMemoryWarning()
        // Dispose of any resources that can be recreated.
    }
    @IBAction func plus(){
        number = number + 1
        label.text = String(number)
        label.font = UIFont.systemFont(ofSize: CGFloat(number)*2+46)
        
    }
