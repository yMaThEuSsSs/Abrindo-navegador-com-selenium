# Abrindo-navegador-com-selenium
Abrindo navegador com selenium e java .
---------------------
package seleniumdificult;

import org.openqa.selenium.WebDriver;
import org.openqa.selenium.firefox.FirefoxDriver;

public class opentestgoogle {
	
	public static void main(String[] args) {
	    System.setProperty("webdriver.gecko.driver", "C:\\Driver mozilla\\geckodriver.exe"); 
		WebDriver driver = new FirefoxDriver();
		driver.get("https://www.youtube.com/");
		System.out.println(driver.getTitle());
		
		
	}

}
