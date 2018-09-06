# Sample
package sample;

import java.util.concurrent.TimeUnit;

import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;
import org.openqa.selenium.firefox.FirefoxBinary;
import org.openqa.selenium.firefox.FirefoxDriver;

public class Test2 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.setProperty("webdriver.firefox.marionette","/home/tectoro/Desktop/usr/geckodriver.exe");
		WebDriver driver = new FirefoxDriver();
		// System.setProperty("webdriver.chrome.driver","/home/tectoro/Desktop/usr/chromedriver.exe");
		
	driver.get("https://www.seleniumhq.org/");
	driver.manage().timeouts().implicitlyWait(100, TimeUnit.SECONDS);
	
	}

}
