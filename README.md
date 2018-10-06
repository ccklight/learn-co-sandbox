class Waiter
 
  attr_accessor :name, :yrs_experience
 
  @@all = []
 
  def initialize(name, yrs_experience)
    @name = name
    @yrs_experience = yrs_experience
    @@all << self
  end
 
  def self.all
    @@all
  end
 
 
  def average_years_experience 
  
  end
  
  def customer_names(names) 
  
  end  
  
  def customer_highest-tip(tip)
   
   end 
   
   def average_tip_seasoned_waiter(tip)
   
   end  
   
   def average_tip_novice_waiter(tip)
   
   end 
 
 
end