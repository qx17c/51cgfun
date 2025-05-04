### [👉👉👉♥♥点此进入♥观看入口👈👈👈](https://mrddrm.github.io/hl.html)
<br></br><br></br><br></br>
   if self.inserted_money < product_info["price"]:
            print(f"错误: 金额不足，还需投入 ¥{product_info['price'] - self.inserted_money:.1f}")
            return False
        
        self.current_selection = product_name
        print(f"已选择: {product_name} (¥{product_info['price']})")
        return True
    
    def complete_purchase(self):
        """完成购买"""
        if not self.current_selection:
            print("错误: 请先选择商品")
            return False
